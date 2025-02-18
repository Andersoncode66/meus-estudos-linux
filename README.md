# meus-estudos-linux.




## Manipulando Arquivos no Linux
### 🔹Exercícios: Navegação pelo Sistema de Arquivos

#### 1️⃣Verificando o Diretório Atual
- Use um comando para exibir o diretório em que você está no momento.

#### 2️⃣Listando Arquivos e Diretórios
- Liste todos os arquivos e pastas no diretório atual, incluindo os ocultos.

#### 3️⃣Mudando de Diretório
- Navegue até o diretório /etc e depois volte para o seu diretório pessoal.

#### 4️⃣Voltando ao Diretório Anterior
- Mude para o diretório /usr e depois retorne ao diretório anterior em um único comando.

#### 5️⃣Acessando o Diretório Raiz
- Vá para o diretório raiz e liste o seu conteúdo.

#### 6️⃣Usando Caminhos Absolutos e Relativos
- Navegue para um diretório de sua escolha usando o caminho absoluto
- Depois, navegue até o outro diretório usando um caminho relativo.

#### 7️⃣Criando e Entrando em Diretórios
- Crie um diretório chamado meus-arquivos dentro do seu diretório pessoal e entre nele.

#### 8️⃣Descobrindo Onde Você Está
- Use um comando para exibir o caminho completo do diretório atual.

#### 9️⃣Contando Arquivos em um Diretório
- Encontre um número total de arquivos e pastas dentro do diretório /home.

#### 🔟Procurando Diretórios Específicos
- Encontre o caminho completo do diretório bin usando um comando apropriado.

#### 💡Dica: Para cada exercício, experimente utilizar os comandos pwd, ls, cd, mkdir, find, entre outros.

---------------------------------------------------------------------------------------------------------------

## Manipulando Arquivos no Linux
### 🔹 Exercícios: Filtrando a Exibição de Arquivos

#### 1️⃣ Listando apenas arquivos ocultos
- Exiba apenas os arquivos ocultos do diretório atual.

#### 2️⃣ Listando arquivos com um determinado formato
- Liste apenas os arquivos com a extensão .txt dentro do diretório /home.

#### 3️⃣ Exibindo arquivos ordenados por tamanho
- Liste os arquivos do diretório atual em ordem crescente de tamanho.

#### 4️⃣ Filtrando arquivos por tamanho específico
- Encontre e exiba apenas os arquivos maiores que 1MB dentro do diretório /var/log.

#### 5️⃣ Exibindo arquivos ordernados por data de modificação
- Liste os arquivos do diretório atual ordenados pela data da última modificação, do mais recente para o mais antigo.

#### 6️⃣ Filtrando arquivos pelo nome
- Exiba apenas os arquivos que contenham a palavra "config" no nome dentro de /etc.

#### 7️⃣ Listando apenas diretórios
- Filtre e exiba apenas os diretórios dentro do diretório /usr.

#### 8️⃣ Filtrando arquivos por permissões
- Exiba apenas os arquivos do diretório atual que têm permissão de execução.

#### 9️⃣ Filtrando arquivos modificados recentemente
- Exiba apenas os arquivos que foram modificados nas últimas 24 horas dentro do diretório /var/log.

#### 🔟 Combinado filtros
- Liste os arquivos .log dentro de /var/log, ordenados do maior para o menor.

##### 💡 Dica: Para resolver os exercícios, experimente utilizar os comandos ls, find, grep, du, sort, e awk.

-----------------------------------------------------------------------------------------------------------

## Manipulando Arquivos no Linux

### 🔹 Exercícios: Localizando Arquivos

#### 1️⃣ Localizando um arquivo específico
- Encontre o arquivo passwd dentro do diretório /etc.

#### 2️⃣ Buscando arquivos por extensão
- Liste todos os arquivos com entensão .conf dentro de /etc.

#### 3️⃣ Procurando arquivos em um diretório específico
- Encontre todos os arquivos .log dentro do diretório /var/log.

#### 4️⃣ Localizando arquivos pelo nome
- Encontre todos os arquivos que contêm palavra "backup" no nome dentro do seu diretório pessoal.

#### 5️⃣ Procurando arquivos ignorando maiúsculas e minúsculas
- Localize todos os arquivos que contenham a palavra "config", sem diferenciar letras maiúsculas e minúsculas.

#### 6️⃣ Buscando arquivos por tamanho
- Encontre arquivos maiores que 10MB dentro do diretório /home.

#### 7️⃣ Filtrando por data de modificação
- Liste todos os arquivos dentro de /var/log que foram modificados nos últimos 7 dias.

#### 8️⃣ Procurando arquivos por tipo
- Localize todos os arquivos que são executáveis dentro de /usr/bin.

#### 9️⃣ Encontrando diretórios específicos
- Encontre o diretório chamado "scripts"em qualquer lugar do sistema.

#### 🔟 Localizando arquivos com usuários específicos
- Encontre todos os arquivos pertencentes ao usuáriros root dentro do diretório /etc.

------------------------------------------------------------------------------------------------------------

## Manipulando Arquivos no Linux

### 🔹 Exercícios: Criando diretórios

#### 1️⃣ Criando um diretórios simples
- Crie um diretório chamado projetos dentro do seu diretório pessoal.

#### 2️⃣ Criando múltiplos diretórios de uma vez
- Crie os diretórios docs, imagens e sripts dentro do diretório projetos.

#### 3️⃣ Criando um diretório dentro de um caminho inexistente
- Crie o diretório /home/seu_usuario/backup/2025 em um único comando, garantindo que os diretórios intermediários sejam criados.

#### 4️⃣ Criando diretórios com nomes compostos
- Crie um diretório chamado meus arquivos (com espaço no nome).

#### 5️⃣ Criando um diretório e entrando nele automaticamente
- Crie um diretório chamado testes e mude para ele imediatamente.

#### 6️⃣ Criando diretórios com estrutura hierárquica
- Em um único comando, crie a seguinte estrutura:

![Capturar_2025_02_18_15_52_58_265](https://github.com/user-attachments/assets/1939d797-85d8-4cad-93b8-6808927cb387)

#### 7️⃣ Criando múltiplos diretórios com um padrão numérico
- Crie os diretórios backup_1, backup_2, .., backup_5.

#### 8️⃣ Criando diretórios com permissões específicas
- Crie um diretório chamado privado com permmissão de acesso apenas para o dono.

#### 9️⃣ Criando diretórios com nomes baseados na data atual
- Crie um diretório chamado backup_YYYY-MM-DD usando a data do sistema.

#### 🔟 Verificando se um diretório já existe antes de criá-lo
- Antes de criar um diretório chamado logs, verifique se ele já existe.

💡 Dica: Para resolver esses exercícios, utilize os comandos mkdir, cd, ls, chmod, date e test.

