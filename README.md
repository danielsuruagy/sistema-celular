# Sistema de Smartphones

Projeto em **C#** para praticar **Programação Orientada a Objetos (POO)**, aplicando herança, abstração e polimorfismo.  
A ideia é simular o comportamento de **smartphones** (Nokia e iPhone), permitindo criar instâncias, fazer chamadas, receber ligações e instalar aplicativos.

## 💻 Tecnologias

- **.NET C#**

## 🚀 Estrutura do Projeto

- **Smartphone (classe abstrata)**  
  Propriedades: Numero, Modelo, IMEI, Memoria  
  Métodos: Métodos: Ligar(); ReceberLigacao(); InstalarAplicativo(string nomeApp) (abstrato)

- **Nokia (classe concreta)**  
  Herda de Smartphone  
  Implementa InstalarAplicativo() específico para Nokia

- **iPhone (classe concreta)**  
  Herda de Smartphone  
  Implementa InstalarAplicativo() específico para iPhone


## 🎯 Objetivos

- Exercitar conceitos de POO em C#: 
- Abstração: classe Smartphone
- Herança: Nokia e iPhone herdam de Smartphone
- Polimorfismo: sobrescrita de InstalarAplicativo()
- Encapsulamento: uso de propriedades privadas e públicas
