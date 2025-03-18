# Projeto Gerador de FakeUser

o projeto consiste em usar uma API Pública para geração de usuários ficticios com informações como nome, email, imagem, estado, pais, entre outros

## Design do projeto

![alt text](image.png)

## API Utilizada

A API utilizada foi a https://randomuser.me/ que fornece informações de usuários através de um json conforme abaixo:

```
{
  "resultados": [
    {
      "Sexo: Feminino ",
      "nome": {
        "título": " Senhorita ",
        "primeiro": " Jennie ",
        "último": " Nichols "
      },
      "localização": {
        "rua": {
          "número": 8929 ,
          "nome": " Valwood Pkwy ",
        },
        "cidade": " Billings ",
        "estado": " Michigan ",
        "país": " Estados Unidos ",
        "código postal": " 63104 ",
        "coordenadas": {
          "latitude": " -69.8246 ",
          "longitude": " 134.8719 "
        },
        "fuso horário": {
          "deslocamento": " +9:30 ",
          "descrição": " Adelaide, Darwin "
        }
      },
      "e-mail": " jennie.nichols@example.com ",
      "Conecte-se": {
        "uuid": " 7a0eed16-9430-4d68-901f-c0d4c1c3bf00 ",
        "nome de usuário": " yellowpeacock117 ",
        "senha": " addison ",
        "sal": " sld1yGtd ",
        "md5": " ab54ac4c0be9480ae8fa5e9e2a5196a3 ",
        "sha1": " edcf2ce613cbdea349133c52dc2f3b83168dc51b ",
        "sha256": " 48df5229235ada28389b91e60a935e4f9b73eb4bdb855ef9258a1751f10bdc5d "
      },
      "sobrenome": {
        "data": " 1992-03-08T15:13:16.688Z ",
        "idade": 30
      },
      "registrado": {
        "data": " 2007-07-09T05:51:59.390Z ",
        "idade": 14
      },
      "telefone": " (272) 790-0888 ",
      "célula": " (489) 330-2385 ",
      "eu ia": {
        "nome": " SSN ",
        "valor": " 405-88-3636 "
      },
      "foto": {
        "grande": " https://randomuser.me/api/portraits/men/75.jpg ",
        "médio": " https://randomuser.me/api/portraits/med/men/75.jpg ",
        "miniatura": " https://randomuser.me/api/portraits/thumb/men/75.jpg "
      },
      "nat": " EUA "
    }
  ],
  "informação": {
    "semente": " 56d27f4a53bd5441 ",
    "resultados": 1 ,
    "página": 1 ,
    "versão": " 1.4 "
  }
}
```

## Funcionalidades

- [ x ] filtro de usuário pelo gênero
- [ x ] filtro de usuário pela nacionalidade
- [ x ] filtro de usuário pela quantidade
- [  ] Mostrar mais informações do usuários: Pais, Estado, Cidade, Telefone
- [  ] Responsividade da tela
- [  ] Aumentar o filtro da quantidade de usuários
- [  ] colocar mais opções de paises

## Contatos

Email: victorddlc21@gmail.com