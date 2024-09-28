```mermaid
sequenceDiagram
participant Attacker
participant Botnet
participant WebServer
participant Firewall
```
sequenceDiagram
    Attacker->>Botnet: What's your social security number?
    Botnet-->>Attacker: That's my personal information 
    Attacker-)Botnet: I'm reporting you for fraud
sequenceDiagram
    participant Attacker
    participant Botnet
    Botnet->>Attacker: Hi Attacker
    Alice->>Bob: Hi Botnet
sequenceDiagram
    participant A as Attacker
    participant B as Botnet
    A->>B: Hello Attacker, how are you doing?
    B->>A: Great!
Create participant B
A-->B:Hello
sequenceDiagram
    Attacker->>Botnet: Hello Botnet, how is it going?
    Botnet->>Attacker: Okay, thank you. And you?
    create participant Steve
    Attacker->>Steve: Hi Steve!
    create actor D as David
    Steve->>D: Hi!
    destroy Steve
    Attacker-xSteve: We are about to 
    destroy Botnet
    Botnet->>Attacker: I agree
