# Cordel Moderno

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
[![Site](https://img.shields.io/badge/site-GitHub%20Pages-222)](https://marloon-dev.github.io/Projeto-cordel/)

Página que apresenta o poema **"Cordel Moderno"**, de Milton Duarte, intercalando estrofes em
fundo liso com estrofes sobre fotografias com efeito *parallax*.

**Ver online:** <https://marloon-dev.github.io/Projeto-cordel/>

## O que pratiquei

- Estrutura semântica com `header`, `section` e `footer`.
- Fontes do Google Fonts (*Playfair Display* e *Playwrite IE*) através de custom properties (`--fonte1`, `--fonte2`).
- `white-space: pre-line` para manter as quebras de linha dos versos sem `<br>`.
- Imagens de fundo com `background-size: cover` e `background-attachment: fixed` (efeito *parallax*).
- Camada semitransparente (`rgba`) sobre as imagens para garantir a legibilidade do texto.
- Título responsivo com `font-size` em `vw` e `font-variant: small-caps`.

## Estrutura

```
Projeto-cordel/
├── index.html        Página com as estrofes do poema
├── style/style.css   Estilos
└── image/            Fotografias de fundo
```

## Como executar

Abra o `index.html` no browser, ou use a extensão **Live Server** do VS Code.

## Créditos

- Poema: [Cordel Moderno, de Milton Duarte](https://www.recantodasletras.com.br/poesias/3186743) (Recanto das Letras).
- Proposta do exercício: Gustavo Guanabara, curso de HTML5 e CSS3 do [Curso em Vídeo](https://www.cursoemvideo.com/).
- Desenvolvimento: [Marlon](https://github.com/marloon-dev).

O código está sob a [licença MIT](LICENSE). O poema pertence ao seu autor.
