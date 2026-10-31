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
    E --> F
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

```mermaid
gantt
    title project schedule
    dateFormat YYYY/MM/DD
    section design
    yoken design    :a1, 2025-01-01, 20d
    kihon     :a2, after a1, 10d
    section development
    front end    :b1, after a2, 20d
    back end     :b2, after a2, 25d
    section test
    whole        :c1, after b2, 10d
```

```mermaid
pie title used languages
    "Java Script" : 40
    "Python" : 30
    "TypeScript" : 20
    "others" : 10
```

```mermaid
stateDiagram-v2
    [*] --> draft
    draft --> review : submit
    review --> approved : approve
    review --> draft : return
    approved --> [*]
```

```mermaid
flowchart
    A[start] --> |confirm| B[execute]
    B --> |execute| C[end]
```