# Arquitetura do Sistema

## 1. Visão Geral

Arquitetura Cliente-Servidor com API RESTful, desacoplando frontend do backend para suportar múltiplas plataformas.

## 2. Diagrama de Componentes

`[Navegador Web (Admin)] --> [API RESTful (PHP/Laravel)] --> [Banco de Dados (MongoDB)]`
`[App Mobile (Membro)] ----> [API RESTful (PHP/Laravel)] ↗`

## 3. Justificativas

- **PHP/Laravel:** Framework robusto para desenvolvimento rápido de APIs.
- **MongoDB:** Banco NoSQL flexível, facilita a evolução do esquema de dados.
- **React/React Native:** Reaproveitamento de código entre web e mobile.
