# Exercício de POO em Java - Sistema de Dispositivos Eletrônicos

## 📌 Descrição do Exercício
Este projeto é um exercício em **Java** para praticar os conceitos fundamentais de **Programação Orientada a Objetos (POO)**.  
Você deverá implementar um sistema de gestão de dispositivos eletrônicos que demonstre os seguintes conceitos:

- **Encapsulamento**
- **Herança**
- **Polimorfismo**
- **Modificadores de acesso** (`private` e `final`)
- **Construtores e métodos getters**

O sistema simula uma **loja de dispositivos eletrônicos**, permitindo o gerenciamento de diferentes tipos de dispositivos com características específicas.

---

## ✅ Requisitos

### Classe Base (Superclasse)
- Criar uma classe chamada **`DispositivoEletronico`**
- Atributos privados: `marca`, `modelo`, `anoFabricacao`
- Atributo **privado e final**: `numeroSerie` (único para cada dispositivo)
- Método **construtor** que inicialize todos os atributos
- Métodos **getters** para acessar os atributos (sem setters para atributos `final`)
- Criar um método chamado **`obterInformacoes()`** que retorne as informações do dispositivo  
  - Esse método deve ser **sobrescrito** nas subclasses para incluir os atributos específicos de cada uma

### Classes Derivadas (Subclasses)
Criar três classes que herdam de **`DispositivoEletronico`**:

- **`Smartphone`** → atributo adicional: `tamanhoTela (double)`
- **`Tablet`** → atributo adicional: `possuiTeclado (boolean)`
- **`Notebook`** → atributo adicional: `capacidadeBateria (int)`

Cada classe deve:
- Ter um **construtor** que inicialize todos os atributos (incluindo os da superclasse)
- **Sobrescrever** o método `obterInformacoes()` de forma apropriada
- Ter métodos **getters** para seus atributos específicos

### Polimorfismo
- Criar objetos das subclasses na classe principal (**`Main`**)
- Chamar o método **`obterInformacoes()`** em cada objeto, demonstrando que o mesmo método se comporta de forma diferente dependendo do tipo de dispositivo
- Demonstrar o uso de **polimorfismo** através de um **array da superclasse** contendo objetos das subclasses

### Encapsulamento
- Todos os atributos devem ser **privados**
- Criar métodos públicos **getters** para acessar os atributos
- Atributos marcados como **`final`** não devem ter setters

---

## 📁 Estrutura do Projeto
