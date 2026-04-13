# 🚀 API Automation Testing - JSONPlaceholder

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Este repositório contém uma suíte de testes automatizados para a API **JSONPlaceholder**, desenvolvida para validar fluxos de usuários e postagens.

---

## 📋 Cenários de Teste


 Método | Objetivo do Teste | Status Esperado |
 :--- | :--- | :--- |
| `GET` | Listar todos os usuários cadastrados | `200 OK` |
| `GET` | Buscar dados de um usuário específico por ID | `200 OK` |
| `POST` | Simular a criação de um novo usuário | `201 Created` |
| `GET` | Filtrar postagens por `userId` | `200 OK` |
| `DELETE`| Validar a exclusão de uma postagem | `200 OK` |

---

## 🛠️ Tecnologias e Validações Aplicadas

- **Validação de Status Code:** Verificação se o servidor retorna o código correto (200, 201).
- **Tempo de Resposta:** Teste de performance garantindo respostas em menos de 500ms.
- **Validação de Body:** Checagem de tipos de dados (String, Number, Array) e presença de campos obrigatórios (como IDs gerados).
- **Scripts em JavaScript:** Automação utilizando o motor do Postman (Chai.js).



## 📑 Documentação e Resultados
Você pode visualizar a explicação detalhada de cada caso de teste e as evidências de sucesso no meu Notion:

👉 [[Notion](https://www.notion.so/API-REST-de-Gerenciamento-de-Usu-rios-341437a022aa8076b252edd0ed23c3a5?source=copy_link)]

Desenvolvido por *Thallyssa Gama* | 📧 [thallyssagama55@gmail.com] | 🔗 [LinkedIn](https://www.linkedin.com/in/thallyssa-gama-265b041b4/)

