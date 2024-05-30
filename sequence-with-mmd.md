```mermaid
sequenceDiagram
  autonumber
  actor Cindrella
  participant Alice
  participant John

  Alice->>John: Hello John, pass my greeting to Cindrella, would u ?  
  John-)Cindrella: Alice said Hi!
  Note over John: John acts as a broker 
  Cindrella-->>John: Thats nice John, let me greet her back  
  Cindrella->>Alice: I ACK that Hi, Alice
```
