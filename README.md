# La Odisea del Zorro (The Fox's Odyssey)

An interactive "choose your own adventure" game following the journey of a rescued fox finding its place in the wild. Built with HTML.

## Story

You are a fox born sick and alone in a desolate forest. At the brink of death, you were rescued by a wildlife caretaker who nursed you back to health. Now recovered, you face your first true choice: go into the unknown wilderness or stay safe. Every decision shapes your destiny.

## Project Structure
```
.
├── inicio/
│   └── index.html          # Starting point of the game
├── capitulos/
│   ├── adentrarse_bosque.html
│   ├── explorar_rio.html
│   ├── seguir_cuervo.html
│   ├── seguir_cuervo_profundo.html
│   ├── investigar_huellas.html
│   ├── retirarse_respetuoso.html
│   ├── defender_posicion.html
│   ├── rio_arriba.html
│   ├── robar_carnada.html
│   ├── huir_inmediato.html
│   ├── buscar_alternativa.html
│   ├── observar_comunidad.html
│   └── explorar_colinas.html
├── finales/
│   ├── final_bueno.html    # Good ending
│   ├── final_neutro.html   # Neutral ending
│   └── final_malo.html     # Bad ending
└── imagenes/               # All game images
```

## Video of functionality

[La odisea del zorro :)](https://youtu.be/xOCQ-COYlhc)

## Game Features

- **13 HTML pages total** - interconnected story branches
- **Multiple decision points** - each page offers 2+ meaningful choices
- **3 distinct endings:**
  - **Good ending:** Find a community and thrive
  - **Neutral ending:** Survive alone in modest safety  
  - **Bad ending:** Lose your freedom

## How to Play

### Running Locally

1. Clone this repository:
```bash
   git clone https://github.com/fatupopzz/lab1_zorro.git
   cd lab1_zorro
```

2. Open the starting page in your browser:
```bash
   open inicio/index.html
   # or
   xdg-open inicio/index.html
```

3. Make your choices by clicking the links

### Running with NGINX

1. Create directory in NGINX:
```bash
   sudo mkdir -p /var/www/html/odisea-del-zorro
```

2. Copy files:
```bash
   sudo cp -r * /var/www/html/odisea-del-zorro/
```

3. Set permissions:
```bash
   sudo chmod -R 755 /var/www/html/odisea-del-zorro
```

4. Access in browser:
```
   http://localhost/odisea-del-zorro/inicio/
```

## Game Paths

The story branches based on your choices:
```
START → Choose path → Make decisions → Reach one of 3 endings

Path 1: Deep Forest
  → Follow crow or investigate tracks
  → Trust and find community (GOOD)
  → OR settle alone (NEUTRAL)
  
Path 2: River Exploration  
  → Go upstream or avoid traps
  → Escape danger (NEUTRAL)
  → OR get trapped (BAD)
```


## Author

**Fatima Navarro**  
Web Technologies Lab 1  
Universidad del Valle de Guatemala, 2026



