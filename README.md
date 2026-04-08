# Proyecto2

## Comandos para usar Docker

### Desarrollo

```bash
./dev up
./dev test
./dev run
./dev watch
./dev bash
./dev down
```

### Produccion

```bash
docker build -t proyecto2:latest .
docker run --rm proyecto2:latest
```