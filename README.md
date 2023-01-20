![](header.png)

- :desktop_computer: Lover of all things code, not limited by framework, platform or anything

- :dragon: Beliver of fantasy

- :art: Self-proclaimed artist

`Configuration:`

```typescript
interface VariableEntity {
    name: string,
    pronouns: string[],
    countryCode: keyof CountryCodes,
    languages: string[],
    normieLangs: string[],
    lifeProviders: string[],
    status: string,
    working: string[]
}

interface CountryCodes {
    "ES",
    "EN",
    "PT",
    "FR",
    "US"
}

export var hadronomyEntity: VariableEntity =  {
    name: "Pablo Hernández Jiménez",
    pronouns: ["he", "him", "his"],
    countryCode: "ES",
    languages: ["javascript", "typescript", "csharp", "c", "html", "python", "css"],
    normieLangs: ["spanish", "english"],
    lifeProviders: ["friends", "programming", "art", "writting"],
    status: "ALIVE",
    working: ["A little bit of everything", "unity", "csharp-libraries", "typescript-frameworks"]
}
```

And yes, I'm a <code>variable</code>

