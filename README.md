# Exercício de Programação Orientada a Objetos em Java - Sistema de Veículos

## 📌 Descrição do Exercício
Este projeto é um exercício simples em **Java** para praticar os conceitos de **Programação Orientada a Objetos (POO)**:  
- **Encapsulamento**  
- **Herança**  
- **Polimorfismo**

O sistema simula uma concessionária, permitindo o gerenciamento de diferentes tipos de veículos.

---

## ✅ Requisitos

### Classe Base (Superclasse)
- Criar uma classe chamada `Veiculo`.  
- **Atributos privados**: `marca`, `modelo`, `ano`.  
- Métodos **getters e setters** para acessar/modificar os atributos.  
- Criar um método chamado `exibirInformacoes()` que mostre as informações do veículo.  
  - Esse método deve ser sobrescrito nas subclasses para incluir os atributos específicos de cada uma.  

---

### Classes Derivadas (Subclasses)
- Criar **duas classes** que herdam de `Veiculo`:  
  - `Carro` → atributo adicional: `quantidadeDePortas`  
  - `Moto` → atributo adicional: `cilindrada`  
- Cada classe deve sobrescrever o método `exibirInformacoes()` de forma apropriada, permitindo o polimorfismo quando chamado na classe principal.

---

### Polimorfismo
- Criar objetos de `Carro` e `Moto` diretamente na classe principal (`Main`).  
- Chamar o método `exibirInformacoes()` em cada objeto, demonstrando que o mesmo método se comporta de forma diferente dependendo do tipo de veículo.

---

### Encapsulamento
- Todos os atributos devem ser **privados**.  
- Criar **métodos públicos (`get` e `set`)** para acessar e modificar os atributos.
