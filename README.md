<<<<<<< HEAD
<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=22&pause=1000&color=00FF00&center=true&vCenter=true&width=600&lines=%F0%9F%94%90+Verificador+de+Senhas+Vazadas;GZN000+%7C+GUGU;Primeiro projeto, me aguardem pra mais+%F0%9F%8E%AD%F0%9F%A5%B7+%E2%9C%94%EF%B8%8F" alt="Typing SVG" />
</p>

# Verificador-senha-vazadas
🔐 Verificador de Senhas Vazadas - Python  Este projeto permite verificar se uma senha já apareceu em **vazam>  > ✅ Ideal para segurança pessoal e educacional. > ❌ Não armazena, nem compartilha senhas.  ---  ## 🚀 Como funciona  - A senha é transformada em **hash SHA-1** - Apenas os **5 primeiros caracteres** são enviados para a API.
=======
# 🛡️ Verificador de Senhas Vazadas
>>>>>>> 8d89924068bf48de9cc90d7b40bd061c3004fc7f

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
