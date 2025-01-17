---
layout: page
title: ""
#subtitle: Prótese para membros superiores
cover-img: /assets/img/mao_espelhada/mirrored_hand.png
---

O projeto consiste na criação de uma prótese robótica de um membro superior, na qual o movimento dos dedos será inicialmente controlado por pela outra mão, por isso o nome **Mão-ESPELHADA**. O controle será feito utilizando uma câmera através de visão computacional.

A mão robótica inicialmente deverá repetir o mesmo movimento feito pela mão, porém isto nem sempre será muito útil, de forma que esse projeto terá bastantes aperfeiçoamentos futuros.

Se faz necessário os conhecimentos como CAD, eletrônica, visão computacional e programação.

Para desenvolver o programa, foi utilizado o *framework* Arduino, a fim de programar o microcontrolador que irá desenvolver os momentos através de alguns potenciômetros. Além disso, há a parte de visão computacional em OpenCV de forma que fosse possível identificar os dedos com uma câmera e enviar os comandos para serem reproduzidos pelo braço robótico. 

<img width="30" src="{{ 'assets/img/github-logo.png' | relative_url }}" alt="logo github"/> **Repositório:** [rascimatec/mao-espelhada](https://github.com/rascimatec/mao-espelhada)

## CAD

O cad foi desenvolvido utilizando o *software* Onshape, um *software* online que facilita sua utilização entre os participantes do projeto. Foi desenvolvido cada dedo e cada falange separadamente para que o design fosse o mais semelhante possível com uma mão humana. Em seguida foi modelada a palma, integrando-a com os dedos. 


<center><img width="420" src="{{ '/assets/img/mao_espelhada/cad.png' | relative_url }}" alt="interface"/></center>


<center><img width="420" src="{{ '/assets/img/mao_espelhada/cadpalma.png' | relative_url }}" alt="interface"/>
<br>Modelagem dos dedos e da mão completa feita no Onshape</center>

### Equipe de Desenvolvimento
<div class="row">
  <div class=" col-xl-auto offset-xl-0 col-lg-4 offset-lg-0">
    <div class="mobile-side-scroller">
      <table class="table-borderless highlight">
        <thead>
          <tr>
            <th><center><img src="{{ 'assets/img/voluntarios/breno_bogea.png' | relative_url }}" width="100" alt="breno" class="img-fluid rounded-circle" /></center></th>
            <th></th>
            <th><center><img src="{{ 'assets/img/voluntarios/tiago_barreto.png' | relative_url }}" width="100" alt="tiago" class="img-fluid rounded-circle"/></center></th>
            <th></th>
            <th><center><img src="{{ 'assets/img/voluntarios/marcella_giovanna.png' | relative_url }}" width="100" alt="marcella" class="img-fluid rounded-circle" /></center></th>
          </tr>
        </thead>
        <tbody>
          <tr class="font-weight-bolder" style="text-align: center margin-top: 0">
            <td width="33.33%"><center>Breno Passos</center></td>
            <td></td>
            <td width="33.33%"><center>Tiago Barreto</center></td>
            <td></td>
            <td width="33.33%"><center>Marcella Giovanna</center></td>
          </tr>
          <tr style="text-align: center" >
            <td style="vertical-align: top"><small><center>Voluntário desde 2021 <p/> Líder do projeto</center></small></td>
            <td></td>
            <td style="vertical-align: top"><small><center>Voluntário desde 2021 <p/> Sub-Líder do projeto</center></small></td>
            <td></td>
            <td style="vertical-align: top"><small><center>Voluntária desde 2018</center></small></td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
