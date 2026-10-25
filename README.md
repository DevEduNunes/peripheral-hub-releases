<div align="center">

<img src="icon.png" width="96" alt="Peripheral Hub">

# Peripheral Hub — versões

**Um único app, preto e roxo, para controlar fone Logitech PRO X 2, teclado Raven68 HE, mouse KYSOAN e o mixer de volume com Arduino.**

</div>

Este repositório contém **somente os instaladores** do Peripheral Hub para Windows, usados também pelo atualizador automático do programa. O código-fonte fica em um repositório privado.

## Baixar

Pegue o `PeripheralHub-Setup-<versão>.exe` mais recente em [Releases](../../releases/latest) e execute. O instalador valida e instala o que faltar (Logitech G HUB, Visual C++, driver do Arduino e Git para o backup), e o programa passa a se atualizar sozinho.

## Segurança das atualizações

- O programa só consulta este repositório (`github.com/DevEduNunes/peripheral-hub-releases`) e baixa apenas daqui.
- Cada instalador é publicado com um arquivo `.sig`: uma assinatura digital **ed25519** feita com uma chave que só o autor possui. O programa confere a assinatura (e o SHA-256) e **se recusa a executar** qualquer arquivo que não bata.
- Nada é instalado sem você clicar em "Baixar e instalar", e o Windows pede permissão de administrador.
- Os instaladores não têm assinatura de código paga (Authenticode); por isso o Windows SmartScreen pode mostrar um aviso na primeira instalação.

Chave pública usada pelo atualizador (ed25519, hex):

```
e150d65c95ae09a4f0271ba6c98ce0636baedf8cb81f5e020ac12e138151dd9d
```

Para conferir manualmente: calcule o SHA-256 do `.exe` e verifique a assinatura (base64, em `.sig`) sobre esse digest com a chave acima.

## Licença

O Peripheral Hub é distribuído sob a licença MIT (`LICENSE`). Componentes de terceiros, incluindo arquivos de fabricantes distribuídos para interoperabilidade, mantêm as próprias licenças — veja `THIRD_PARTY_NOTICES.md`. Projeto independente, sem vínculo com Logitech, Raven, KYSOAN ou Arduino.
