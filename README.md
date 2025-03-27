# 🇧🇷 **Conversor de Moedas - Console App (.NET 9) 🚀**

***(English version below)***

## **📌 Sobre o Projeto**

Este é um projeto de estudo desenvolvido em **.NET 9**, que realiza a conversão de moedas em tempo real, consumindo uma API de câmbio. Ele foi estruturado seguindo os princípios do **SOLID**, garantindo código modular, reutilizável e de fácil manutenção.

## **📁 Estrutura do Projeto**

```
CopiarEditar
📦 ConversorMoedas
 ┣ 📂 Entities
 ┃ ┗ 📜 Coins.cs
 ┣ 📂 Factories
 ┃ ┗ 📜 CoinsFactory.cs
 ┣ 📂 Mains
 ┃ ┗ 📜 MainCoins.cs
 ┣ 📜 Program.cs
 ┗ 📜 README.md

```

- `Entities/` → Contém as classes que representam as moedas.
- `Factories/` → Implementa o padrão **Factory** para criar instâncias de moedas.
- `Mains/` → Controla o fluxo principal do programa e a interação com o usuário.

## **⚙️ Como Executar**

### **1️⃣ Clonar o Repositório**

```
git clone git@github.com:User/ConversorDeMoedas.git
cd currency-converter
```

### **2️⃣ Configurar a API**

O projeto utiliza uma API externa para obter taxas de câmbio. Configure sua **API Key** no código ou em um arquivo de configuração.

### **3️⃣ Executar o Projeto**

```
dotnet run
```

### **4️⃣ Exemplo de Uso**

Digite os códigos das moedas desejadas (exemplo: **USD para BRL**) e veja a conversão em tempo real.

## **📌 Princípios SOLID Aplicados**

✅ **S** - **Single Responsibility Principle** → Separação clara das responsabilidades.

✅ **O** - **Open/Closed Principle** → Facilidade de extensão sem modificar o código base.

✅ **L** - **Liskov Substitution Principle** → Uso correto de abstrações e herança.

✅ **I** - **Interface Segregation Principle** → Interfaces específicas para evitar dependências desnecessárias.

✅ **D** - **Dependency Inversion Principle** → Implementação de injeção de dependência para desacoplamento.

## **📜 Objetivo**

Este projeto foi criado exclusivamente para fins **educacionais**, com o objetivo de praticar boas práticas de programação e o uso de APIs externas em C#.

## **📜 Licença**

Este projeto é open-source e pode ser utilizado livremente.

---

# 🇺🇸 **Currency Converter - Console App (.NET 9) 🚀**

## **📌 About the Project**

This is a **.NET 9** study project that performs real-time currency conversion by consuming an exchange rate API. It follows **SOLID** principles, ensuring modular, reusable, and maintainable code.

## **📁 Project Structure**

```
CopiarEditar
📦 CurrencyConverter
 ┣ 📂 Entities
 ┃ ┗ 📜 Coins.cs
 ┣ 📂 Factories
 ┃ ┗ 📜 CoinsFactory.cs
 ┣ 📂 Mains
 ┃ ┗ 📜 MainCoins.cs
 ┣ 📜 Program.cs
 ┗ 📜 README.md

```

- `Entities/` → Contains the classes representing currencies.
- `Factories/` → Implements the **Factory** pattern to create currency instances.
- `Mains/` → Controls the program flow and user interaction.

## **⚙️ How to Run**

### **1️⃣ Clone the Repository**

```
git clone git@github.com:User/ConversorDeMoedas.git
cd currency-converter
```

### **2️⃣ Configure the API**

The project uses an external API to fetch exchange rates. Set up your **API Key** in the code or a config file.

### **3️⃣ Run the Project**

```
dotnet run
```

### **4️⃣ Usage Example**

Enter the currency codes you want to convert (e.g., **USD to BRL**) and get real-time conversion rates.

## **📌 SOLID Principles Applied**

✅ **S** - **Single Responsibility Principle** → Clear separation of responsibilities.

✅ **O** - **Open/Closed Principle** → Easy extension without modifying the base code.

✅ **L** - **Liskov Substitution Principle** → Proper use of abstractions and inheritance.

✅ **I** - **Interface Segregation Principle** → Specific interfaces to avoid unnecessary dependencies.

✅ **D** - **Dependency Inversion Principle** → Implementation of dependency injection for decoupling.

## **📜 Purpose**

This project was created **for educational purposes**, focusing on best coding practices and API consumption in C#.

## **📜 License**

This project is open-source and free to use.
