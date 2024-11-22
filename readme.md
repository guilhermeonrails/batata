### **Passo a Passo**

**Inicialize um repositório Git:**
   ```
   git init
   ```

Este comando transforma o diretório atual em um repositório Git.

Adicione todos os arquivos:

```
git add .
```


O ponto (.) indica que todos os arquivos e subdiretórios serão adicionados ao próximo commit.

Faça o primeiro commit:

```
git commit -m "Mensagem descritiva do commit"
```


Substitua "Mensagem descritiva do commit" por uma mensagem que explique as alterações. Exemplo: git commit -m "Primeira versão do projeto".

Crie um remote:

```
git remote add origin [URL inválido removido]
```

Substitua seu_usuario e seu_repositorio pelos seus dados no GitHub.

Envie o projeto para o GitHub:

```
git push origin main
```

Este comando envia todas as alterações para o branch main do seu repositório remoto.

Explicando os Comandos
- git init: Cria um novo repositório Git.
- git add .: Adiciona arquivos ao próximo commit.
- git commit -m "mensagem": Cria um commit com a mensagem especificada.
- git remote add origin https://...: Adiciona um remote chamado origin que aponta para o seu repositório no GitHub.
- git push -u origin main: Envia as alterações locais para o branch main remoto.
