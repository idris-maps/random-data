# Rosling

```typescript
type Years = number[]

interface Country {
  country: string
  geo: string
  code: string
  region: string
  gdpCapita: Years
  pop: Years
  lifeExpect: Years
}

interface Dataset {
  years: Years
  countries: Country[]
}
```

source: [Gapminder](https://www.gapminder.org/data)
