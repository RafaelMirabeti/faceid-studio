# FaceID Studio

Protótipo educacional de visão computacional para cadastrar amostras faciais e comparar rostos detectados pela câmera.

## Como executar

1. Baixe ou clone este repositório.
2. Abra a pasta com um servidor local (recomendado), por exemplo a extensão **Live Server** no VS Code.
3. Abra o endereço local gerado e permita o acesso à câmera.
4. Aguarde os modelos carregarem, inicie a câmera e cadastre amostras com nomes e ângulos diferentes.

> O navegador geralmente exige **HTTPS ou localhost** para permitir o acesso à câmera. A biblioteca e os modelos são carregados pela internet.

## Tecnologias

- HTML, CSS e JavaScript
- [face-api.js](https://github.com/justadudewhohacks/face-api.js)
- Tiny Face Detector, Face Landmark 68 e Face Recognition

## Privacidade e limitações

O protótipo armazena descritores faciais numéricos no `localStorage` do navegador; não salva imagens deliberadamente. Descritores faciais continuam sendo dados biométricos sensíveis. Cadastre apenas pessoas que deram consentimento, não publique dados biométricos e limpe os cadastros em dispositivos compartilhados.

O resultado é probabilístico, pode identificar incorretamente ou não reconhecer alguém. **Não use para controle de acesso, segurança, vigilância ou decisões importantes.** Este projeto é demonstrativo e não constitui um sistema confiável de verificação de identidade.

## Licença

Nenhuma licença específica foi definida para este projeto.