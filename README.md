# Formação de Talentos - 2018

O problema com a data é meio complexo, mas praticamente, quando utilizamos a função 'toLocaleDateString()' estamos pegando a data do servidor local que estamos utilizando. Provavelmente isso acabou conflitando com o DateTime da API.

A solução que encontrei foi criar um input que não é visível ao usuário com a data convertida no formato JSON e então esse valor é enviado para a API.
