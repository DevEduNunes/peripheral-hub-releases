# Avisos de terceiros — Peripheral Hub

O código do Peripheral Hub é licenciado sob a MIT (arquivo `LICENSE`). O programa instalado usa, ou baixa durante a instalação, os componentes abaixo, que **não** são cobertos pela licença MIT e mantêm as licenças dos seus autores.

## Bibliotecas incluídas no programa

| Componente | Versão | Licença |
|---|---|---|
| Python e Tcl/Tk | 3.13 | PSF License / Tcl/Tk License |
| hidapi (pacote `hidapi`) | 0.15 | BSD-3-Clause (escolhida entre as licenças oferecidas pelo projeto) |
| websocket-client | 1.9 | Apache-2.0 |
| Pillow | 12.x | MIT-CMU (HPND) |
| pystray | 0.19 | LGPL-3.0 — carregada dinamicamente pelo Python; pode ser substituída por outra cópia da biblioteca. Código-fonte: https://github.com/moses-palmer/pystray |
| pycaw | 2026 | MIT |
| comtypes | 1.4 | MIT |
| pyserial | 3.5 | BSD-3-Clause |
| psutil | 7.x | BSD-3-Clause |
| cryptography | 50.x | Apache-2.0 OU BSD-3-Clause |
| PyInstaller (empacotamento) | 6.x | GPL-2.0-or-later com exceção que permite distribuir programas empacotados |

## Arquivos de fabricantes distribuídos para interoperabilidade

- **`HIDUsb.dll` e `Config.ini` (mouse KYSOAN/Kysona)** — © do respectivo fabricante, software proprietário. É distribuído sem modificações, apenas para que o Peripheral Hub consiga conversar com o mouse do próprio usuário. Não é coberto pela licença MIT. Se você é o titular dos direitos e deseja a remoção, abra uma issue ou escreva para o autor.
- **Dados de posição das teclas do Raven68 HE** — coordenadas do desenho do teclado, derivadas do arquivo de layout do Raven Driver, usadas apenas para desenhar o mapa de teclas.
- **Protocolos de comunicação** — descobertos por observação do tráfego dos próprios aparelhos do autor, para fins de interoperabilidade.

## Baixados durante a instalação (não fazem parte deste projeto)

- **Logitech G HUB** — baixado do site da Logitech e instalado sob os termos da Logitech, apenas se não estiver presente. O Peripheral Hub usa a API local do G HUB para controlar o fone.
- **Microsoft Visual C++ Redistributable** — baixado da Microsoft, sob os termos da Microsoft.
- **Git for Windows** (opcional, usado só no backup de configurações) — GPL-2.0.

## Marcas

Logitech, G HUB, PRO X 2 LIGHTSPEED, Raven68, Raven Driver, KYSOAN, Kysona, Arduino, Discord, Valorant e outras marcas citadas pertencem aos seus donos. O Peripheral Hub é um projeto independente, sem vínculo, patrocínio ou aprovação dessas empresas.

O ícone é derivado da identidade visual do projeto HushRig (mesmo autor).
