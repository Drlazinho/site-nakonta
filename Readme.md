# Frontend do Site Nakonta - Nova versão 1

![](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)


Site de Captura de Clientes para usos de cartões de créditos desenvolvido em um Freela.

## Detalhes do Projeto
* HTML5;
* CSS3 Interno e Inline - [Reaproveitando do email-marketing](https://github.com/Drlazinho/email-marketing-Nakonta);
* FontAwesome para ícones;
* ScrollReviews para animações;
* Javascript - O javascript é interno, mas neste repositório,eu isolei uma cópiad do JS para fins didáticos;
* Expresões Regulares (Regex);
* Responsive Web;
* Formulário com validação de entradas;
    * Número com tamanho mínimo e máximo e tipo(number) aceitável;
    ~~~~javascript
    //Validação de Numero de Telefone
     onlynumbers(input) {
    let re = /^[0-9]+$/;;
    let inputValue = input.value;
    let errorMessage = `Este campo não aceita letras e nem caracteres especiais`;
    if(!re.test(inputValue)) {
      this.printMessage(input, errorMessage);
    }
  }
    ~~~~
    * Email com formato e tamanho mínimo aceitável;
    * Nome com tamanho mínimo aceitável;

## Resultado

[https://site-nakonta.vercel.app/](https://site-nakonta.vercel.app/)

<img src="./images/site-nakonta.png" style="width:40%">

Segunda Página -(obs: não conectada)
[https://site-nakonta.vercel.app/carts.html](https://site-nakonta.vercel.app/carts.html)

## Colaboradores

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/79115354?v=4" width="100px;" alt="Foto de Lázaro Pimentel no GitHub"/><br>
        <sub>
          <b>Lázaro Pimentel</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

