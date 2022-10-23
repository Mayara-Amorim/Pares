

# TROJAN PÁRIS
>STATUS: Concluído
## Descrição:
### Inspirado na Ilíada de Homero, o Trojan Páris foi desenvolvido para estudo e direcionado ao S.O Windows.


## Funcionalidades:
* Conseguimos fazer com que o usuário se conecte a você através do protocolo https 
* Controle a maquina do usuário

## Cuidados:
* Para que esse script funcione será necessario o uso de NetCat

## Tecnologias
<table>
  <tr>
    <td>Python</td>
    <td>NetCat</td>
  </tr>
</table>

## Como rodar a aplicação?

  1. Ter um navegador e conexão com a internet!
  2. Baixar NetCat
  3. Adicionar os arquivos baixados ao path do Windows
  4. Apos isso, no CMD, digite nc [endereco ip que quer se conectar seguido pela porta] -v
  5. No script em python coloque o endereco ip da maquina que quer se conectar na variavel CCIP e salve
  6. No CMD digite nc -lvc 443
  7. Rode o script em python
  8. No terminal, crie pastas, exclua arquivos a vontade!
  
  ## Teste utilizando sua maquina
  1. no CMD, digite: ipconfig para descobrir seu endereço IPv4
  
