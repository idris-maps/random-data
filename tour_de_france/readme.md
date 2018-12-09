# Etapes Tour de France 

```typescript
interface Place {
  id: number
  name: string
  coordinates: number[]
}

type Etape = [
  placeIdStart: number,
  placeIdEnd: number
] 

interface Year {
  year: number
  etapes: Etape[]

interface Dataset {
 places: Place[]
 years: Year[]
}

```

sources:
 * https://histo.letour.fr
 * [OSM nominatim](https://nominatim.openstreetmap.org/)
