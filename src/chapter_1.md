# Chapter 1
```kroki-mermaid
graph TD
  A[ Anyone ] -->|Can help | B( Go to github.com/yuzutech/kroki )
  B --> C{ How to contribute? }
  C --> D[ Reporting bugs ]
  C --> E[ Sharing ideas ]
  C --> F[ Advocating ]
```

<kroki type="erd">
  [Person]
  *name
  height
  weight
  +birth_location_id

  [Location]
  *id
  city
  state
  country

  Person *--1 Location 
</kroki>