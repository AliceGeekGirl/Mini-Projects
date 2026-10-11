# ProofFile

**Verifying digital contract integrity with SHA-256 and Solana.**

ProofFile is a web application that helps companies register digital contracts and allows clients to verify whether a PDF matches the originally registered document.

## 🌐 About the Project | Sobre o Projeto

**EN**

ProofFile provides a way to verify the integrity of digital contracts. Companies register a contract and receive a verification code. Clients can submit the code and the PDF to check whether the document matches the original registered file.

**PT-BR**

O ProofFile é uma aplicação web que permite às empresas registrar contratos digitais e aos clientes verificar se um arquivo PDF corresponde ao documento originalmente registrado.

A empresa registra o contrato e recebe um código de verificação. O cliente utiliza esse código e envia o PDF para conferir se o documento corresponde ao arquivo original.

## 🎯 The Problem | O Problema

Digital documents can be modified after they are shared. It may be difficult for recipients to determine whether a PDF matches the originally registered version.

Document integrity verification helps provide greater transparency between companies and clients.

Documentos digitais podem ser modificados depois de compartilhados. Por isso, pode ser difícil confirmar se um PDF corresponde à versão originalmente registrada.

A verificação da integridade dos documentos ajuda a promover mais transparência entre empresas e clientes.

## ⚙️ How It Works | Como Funciona

1. **Contract registration:** A company submits a PDF contract.
2. **Hash generation:** ProofFile calculates the document's SHA-256 hash.
3. **Record storage:** Contract metadata is stored in PostgreSQL, and verification data is recorded on Solana Devnet using the Memo Program.
4. **Document verification:** The client submits the verification code and PDF.
5. **Hash comparison:** ProofFile compares the submitted document's hash with the registered hash and reports whether they match.

### Português

1. **Registro do contrato:** A empresa envia um contrato em PDF.
2. **Geração do hash:** O ProofFile calcula o hash SHA-256 do documento.
3. **Armazenamento do registro:** Os metadados do contrato são armazenados no PostgreSQL, e os dados de verificação são registrados na Solana Devnet usando o Memo Program.
4. **Verificação do documento:** O cliente informa o código de verificação e envia o PDF.
5. **Comparação dos hashes:** O sistema compara o hash do arquivo enviado com o hash registrado e informa se correspondem.

## 🛠️ Technologies | Tecnologias

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python, Flask
- **Database:** PostgreSQL, hosted on Neon
- **Blockchain:** Solana Devnet
- **Solana Program:** Memo Program
- **Document integrity:** SHA-256

## 🔐 Scope and Limitations | Escopo e Limitações

ProofFile checks whether a submitted PDF matches the registered document by comparing their hashes. It does not determine whether a contract is legally valid, fair, or authentic in its original creation.

The current project uses Solana Devnet for development and demonstration purposes.

O ProofFile verifica se um PDF corresponde ao documento registrado por meio da comparação dos hashes. O sistema não determina se um contrato é legalmente válido, justo ou autêntico em sua criação original.

O projeto utiliza a Solana Devnet para desenvolvimento e demonstração.

## 🚀 Hackathon Project | Projeto de Hackathon

Developed for the Colosseum hackathon, exploring how blockchain technology can support digital document integrity verification.

Desenvolvido para o hackathon Colosseum, explorando como a tecnologia blockchain pode contribuir para a verificação da integridade de documentos digitais.

## 🔗 Repository | Repositório

[View the ProofFile project on GitHub](https://github.com/AliceGeekGirl/Projects-and-Activities/tree/main/ProofFile)

[View the main repository](https://github.com/AliceGeekGirl/Projects-and-Activities)
