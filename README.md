<img src="https://img.shields.io/badge/Docker-Multi Stage%20-blue">
<img src="https://img.shields.io/badge/Go-Lang%20-blue">

# Imagem Docker Full Cycle

Essa é uma imagem Docker criada com a linguagem Go que exibe a mensagem "Full Cycle Rocks!!" quando executada. Ela foi criada como parte do desafio do Full Cycle Developer, utilizando o recurso de multi-stage do Docker e a imagem oficial **scratch** como base da imagem final, o que nos permitiu ter uma imagem final menor que 2MB.

## Como usar essa imagem

Para usar essa imagem, você precisa ter o Docker instalado na sua máquina. Em seguida, execute o seguinte comando:

```docker
docker run rogeriostos/fullcycle
```

Isso irá executar a imagem e exibir a mensagem "Full Cycle Rocks!!"
