## index

- [How to install](#how-to-install)
- [How to use](#how-to-use)
- [Third party](#third-party)

## How to install

npm is necessary

## How to use

open the textbox

## Third party

third party

## How to set up

> [!IMPORTANT]
> node.js 24 is required.

> [!TIP]
> nvm is useful to switch node.js versions.

> [!CAUTION]
> Follow the rule.

> [!WARNING]
> `sudo npm install` is not good to use.

> [!NOTE]
> Windows is recommended.

```mermaid
flowchart TB
    A([Start]) --> B[get data]
    B --> C{data exists?}
    C --> |Yes| D[display data]
    C --> |No| E[error]
    D --> F([End])
    E --- G((test))
    G -.- H(test)
    H --> F
```

```mermaid
sequenceDiagram
    participant U as user
    participant F as front end
    participant A as API
    participant D as database

    U->>F: click login button
    F->>A: POST /login
    A->>D: search user
    D-->>A: user data
    A-->>F: publish token
    F-->>U: display dashboard
```


