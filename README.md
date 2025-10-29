# SicurezzaDelleAppMod1_2026_builder

Builder per il tool di supporto per il corso di Sicurezza delle Applicazioni - Modulo 1 presso il DISEGIM UniParthenope a Nola

## Build

```bash
docker buildx bake --push -f compose.yaml 
```

## Installazione

```bash
docker pull ghcr.io/sicurezzaappdisegimuniparthenope/sicurezzadelleappmod1_2026_builder:latest
```

## Uso

```bash
docker run -it --rm ghcr.io/sicurezzaappdisegimuniparthenope/sicurezzadelleappmod1_2026_builder
```

## Licenza

Questo progetto è concesso in licenza sotto la Licenza MIT. Vedi il file LICENSE per i dettagli
