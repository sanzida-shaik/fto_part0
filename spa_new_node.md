```mermaid
sequenceDiagram
    participant browser
    participant server
    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa 
    server->>browser: HTML document along with css file, JavaScript file, and loaded json contents
```
