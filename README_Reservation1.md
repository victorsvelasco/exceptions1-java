# 🏨 Reservation System (Projeto - Tratamento de Exceções em Java)

Este projeto foi desenvolvido como parte do curso de **Java Completo - Programação Orientada a Objetos + Projetos** do professor [Nélio Alves](https://github.com/acenelio).

O objetivo principal é aplicar **tratamento de exceções** em Java, simulando um sistema simples de **reservas de hotel**.

---

## 🚀 Objetivo do Projeto

Criar um programa que:
1. Receba o número do quarto e as datas de **checkin** e **checkout**.
2. Calcule a **duração da estadia**.
3. Permita **atualizar** as datas da reserva.
4. Faça **validações** e trate erros usando exceções personalizadas.

---

## 🧱 Estrutura do Projeto

```
src/
├── application/
│   └── Program.java        # Classe principal (entrada do programa)
├── model/
│   ├── entities/
│   │   └── Reservation.java  # Entidade que representa a reserva
│   └── exceptions/
│       └── DomainException.java  # Exceção personalizada para regras de negócio
```

---

## 💡 Conceitos Aplicados

- Programação Orientada a Objetos (POO)
- Encapsulamento e classes de entidade
- Lançamento e tratamento de exceções (`try`, `catch`, `throw`)
- Criação de exceções personalizadas
- Boas práticas de validação de dados

---

## 🧩 Exemplo de Execução

```
Room number: 8021
Check-in date (dd/MM/yyyy): 15/10/2025
Check-out date (dd/MM/yyyy): 20/10/2025
Reservation: Room 8021, check-in: 15/10/2025, check-out: 20/10/2025, 5 nights

Enter data to update the reservation:
Check-in date (dd/MM/yyyy): 17/10/2025
Check-out date (dd/MM/yyyy): 22/10/2025
Reservation: Room 8021, check-in: 17/10/2025, check-out: 22/10/2025, 5 nights
```

**Exemplo de erro tratado:**
```
Error in reservation: Check-out date must be after check-in date
```

---

## ⚙️ Tecnologias Utilizadas

- **Java 17**
- **Eclipse IDE**
- **Git / GitHub** para versionamento

---

## 🧠 Aprendizado

Neste projeto, foi possível compreender:
- A importância do tratamento de erros controlado.
- Como criar e lançar exceções específicas para regras de domínio.
- A diferença entre exceções **checked** e **unchecked**.

---

## 📄 Licença

Este projeto foi criado para fins educacionais com base nas aulas do curso do **Nélio Alves**.  
Sinta-se à vontade para clonar e estudar o código.

---

## ✍️ Autor

**Victor Sampaio**  
💻 Estudante de Java | Curso do Nélio Alves  
🔗 [Meu GitHub](https://github.com/victorsvelasco)
