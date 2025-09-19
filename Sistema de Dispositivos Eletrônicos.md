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


---

## 🎯 Objetivos de Aprendizado
- **Herança**: Pratique a criação de uma hierarquia de classes onde subclasses herdam características da superclasse  
- **Polimorfismo**: Implemente métodos que se comportam de maneira diferente em cada subclasse  
- **Encapsulamento**: Proteja os dados usando modificadores de acesso `private` e forneça acesso controlado através de métodos getters  
- **Modificador `final`**: Use o modificador `final` para atributos que não devem ser alterados após a inicialização  
- **Construtores**: Aprenda a criar construtores que inicializem objetos corretamente, incluindo a chamada ao construtor da superclasse  

---

## 📋 Tarefas
- [ ] Implementar a classe base **`DispositivoEletronico`** com todos os atributos e métodos especificados  
- [ ] Criar as três subclasses (**`Smartphone`**, **`Tablet`**, **`Notebook`**) que herdam de `DispositivoEletronico`  
- [ ] Em cada subclasse, implementar o método `obterInformacoes()` para incluir informações específicas do dispositivo  
- [ ] Na classe `Main`, criar instâncias de cada tipo de dispositivo e demonstrar o polimorfismo  
- [ ] Certificar-se de que todos os atributos estão adequadamente encapsulados e acessíveis apenas através de métodos getters  

---

