Repositório dedicado aos arquivos, ferramentas e recursos utilizados no meu projeto e pesquisa pública de Hackintosh.

## 📂 Configurações disponíveis

### Samsung Book X40

EFI destinada ao modelo Samsung.

- **Modelo:** NP550XCJ-XF1BR
- **Pasta:** `Mac-53FDB3D8DB8CA971`
- **EFI:** [Acessar EFI](./NP550XCJ-XF1BR/Mac-53FDB3D8DB8CA971/EFI)

## 📥 macOS Recovery

O macOS Recovery pode ser baixado utilizando a ferramenta `macrecovery.py`, disponibilizada pelo projeto OpenCore.

### Comando de download

```bash
python3 macrecovery.py -b <Model> -m <MLB> download
```

**Descrição dos parâmetros:**

| Parâmetro | Função |
|---|---|
| `-b <Model>` | Identificador Board ID utilizado na solicitação. |
| `-m <MLB>` | Identificador MLB (*Main Logic Board*). |
| `download` | Inicia o download dos arquivos de recuperação. |

### Arquivos gerados

- `BaseSystem.dmg`
- `BaseSystem.chunklist`

Esses arquivos são utilizados na preparação da recuperação e instalação do macOS.

## 🛠️ Ferramentas

### OCAuxiliaryTools

Ferramenta utilizada para configurar, editar e gerenciar arquivos do OpenCore, incluindo `Config.plist`.

- **Repositório:** [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools)