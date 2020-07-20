---
layout: post
title:  "Heroku x DigitalOcean"
date:   2020-07-20 18:00:00 -0300
categories: python, heroku
---

Para começar no [Heroku][heroku] é fácil e grátis no plano Free e Hobby você tem de 550-1000 horas gratuitas para utilizar os Dynos, como são chamados os containers no Heroku, apesar de fazerem parte de um ambiente compartilhado, são máquinas virtuais completamente independentes umas das outras.

Para começar na [DigitalOcean][DigitalOcean] você pode começar com um "Droplet" de $ 5, no qual você poderá escolher o sistema operacional e instalar manualmente o que precisar ou poderá utilizar uma imagem pronta do [Marketplace][Marketplace] da DigitalOcean.

Quais as principais vantagens de utilizar o Heroku?

O Heroku é um serviço de [PaaS - Platform as a Service][PaaS], que basicamente cuida de toda a implementação e hospedagem do seu Web App na nuvem, garantindo que você tenha todas as vantagens da nuvem sem a responsabilidade de manter toda a infraestrutura de hospedagem que pode se tornar complexa a medida que seu App crescer.

A principal vantagem de utilizar esse tipo de serviço é que você poderá focar 100% dos seus esforços no seu App.

Quais as principais vantagens de utilizar a DigitalOcean?

 A depender da sua aplicação a [DigitalOcean][DigitalOcean] que é um serviço de nuvem focado em Desenvolvedores pode ser uma opção melhor e mais barata, porém, você precisa por a mão na massa para configurar os Droplets como são chamadas as máquinas virtuais na [DigitalOcean][DigitalOcean].

 A DigitalOcean pode ser muito atrativa para quem tem mais facilidades com a configuração dos Droplets via linha de comando ou se já houver uma imagem no [Marketplace][Marketplace] da DigitalOcean para o que você quer rodar, por exemplo, você pode querer hospedar sites em Wordpress, com apenas $ 5 e alguns cliques você consegue fazer isso na DigitalOcean através da imagem do Plesk Obisidian que permite até 3 sites sem cobrança de mensalidade.

Conclusão

Um serviço não é melhor que o outro, eu já utilizei os dois e tudo irá depender do que você quer construir e a que proporções suas aplicações podem chegar, além é claro das tecnologias que você irá utilizar, a [DigitalOcean][DigitalOcean] é bem mais aberta nesse sentido uma vez que você pode configurar o Droplet do zero, enquanto que o [Heroku][heroku] será mais travado porém será muito mais rápido pois você desenvolve no [VS Code][VS Code], sobe pro [GitHub][GitHub] e o [Heroku][heroku] faz o resto por você.

[heroku]: https://heroku.com
[PaaS]: https://pt.wikipedia.org/wiki/Plataforma_como_serviço
[DigitalOcean]: https://digitalocean.com
[Marketplace]: https://www.digitalocean.com/products/marketplace/
[GitHub]: https://github.com
[VS Code]: https://code.visualstudio.com