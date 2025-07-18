# 🛡️ Verificador de Senhas Vazadas

Projeto em **Python** que permite verificar se uma senha foi exposta em vazamentos de dados, usando a API do [Have I Been Pwned](https://haveibeenpwned.com/).  
Ideal para **uso pessoal, educativo e segurança preventiva**.

> ⚠️ Este script **NÃO envia sua senha completa para a internet.**  
Ela é transformada em `hash SHA-1`, e apenas os **5 primeiros caracteres** são enviados — respeitando o método de **k-Anonymity** da API.

---

## 📥 Como Baixar e Usar

### No Termux ou Linux:

```bash
git clone https://github.com/GZN000/Verificador-senhas-vazadas.git
cd Verificador-senhas-vazadas
pip install requests 
python verificador.py

```
### 💻 Exemplo de Uso

```bash
Digite a senha para verificar:
> minhaSenha123
Senha encontrada em 5 vazamentos! ⚠️
```
## ⚙️ Requisitos

```
★ Python 3  
★ Módulo `requests` instalado
```
## ©️ Autor:
```
GZN000 (GUGU🎭🥷)
```
## 📄 Licença

Este projeto não possui uma licença aberta. Todos os direitos são reservados ao autor.
