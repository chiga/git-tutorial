---
layout: post
title: "Configurações"
description: "Configuração do git pelo bash."
date:   2020-05-10 19:00:00 -0300
categories: start blog
by: 'Chiga'
icon: 'settings'
questions:
  - question: 'Como configurar o git?'
    answer: 'Todas as instruções para configuração estão descritas abaixo.'
    image: "/gifs/config.gif"
---


# Configurando o Git
-----
<br>

> **Com o botão direito do mouse em uma pasta de Projetos clique em "Git Bash Here" conforme a imagem abaixo:**
> 
> ![install](./../assets/img/config/conf1.png)

> **Com o bash aberto começaremos a digitar as configurações**
>
> ![install](./../assets/img/config/conf2.png)


* Git global setup:
  ```bash
  $ git config --global user.name 'seuNome' [Enter]
  $ git config --global user.email 'seuEmail' [Enter]
  $ git config --global mergetool.p4merge.path 'C:Program Files\Perforce\p4merge.exe' [Enter]
  $ git config --global merge.tool p4merge [Enter]
  ```
<br>

* Para verificar se seu Nome e Email estão configurados digite:
  ```bash
  $ git config --list
  ```
![install](./../assets/img/config/conf3.png)

<br>

