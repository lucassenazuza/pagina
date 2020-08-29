## Projetos Desenvolvidos - Eng. Lucas Sena Zuza

  Essa Página contém alguns dos projetos que estou desenvolvendo. Um portifólio para que pessoas interessadas no que estou desenvolvendo psosam me procurar para trocarmos mais informações.
  
## ESP32/ESP32-CAM
  Os projetos abaixos foram criados para atender algumas demandas no setor de Vending Machines. Na primeira foto, temos essa simples que pagína permite acompanhar o que acontece em cada uma das prateleiras de uma geladeira. Para isso, é feito uso da ESP32-CAM por prateleira, essa poderosa câmera, consegue gerar um servidor web com stream, e esse stream é exibido na página. 
![Image](https://github.com/lucassenazuza/pagina/blob/gh-pages/img1.png)
  Outro Pagína para ajudar nos problemas de Vending machines, faz o controle de aberturas de portas e acionamento de travas. No sistema onde a página esta hospedada, temos uma ESP32 usando 3 GPIO's, uma para leitura do sensor magnético da porta, outra para leitura do estado da tranca e a última para acionamento da tranca.
![Image](https://github.com/lucassenazuza/pagina/blob/gh-pages/img2.png)

## Reconhecimento de Produtos com Processamento de Imagens

  Um projeto que trabelhei recentemente foi o de treinamento de redes Neurais para reconhecer produtos de limpeza. Os produtos estão posicionados dentro de uma gôndola, e foram tiradas várias fotos para o treinamento do algoritmo. Depois de tirada as fotos, foi feito a demarcação das **_Bouding boxes_**, para mostrar ao algoritmo como identificar cada produto. No processo usei o **Algoritmo Yolov3** e o framework **Darknet**. Mais informações do algoritmo: <a href="https://github.com/AlexeyAB/darknet">Darknet</a>

![Image](https://github.com/lucassenazuza/pagina/blob/gh-pages/img3.jpg)
![Image](https://github.com/lucassenazuza/pagina/blob/gh-pages/img4.jpg)
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block
# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/lucassenazuza/pagina/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
