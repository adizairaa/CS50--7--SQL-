🎶 Songs - Consultas SQL com Spotify (CS50)


💡 Sobre o Projeto
Este repositório contém as soluções para o Exercício 1: Songs do curso CS50, no qual você vai explorar um banco de dados do Spotify com as 100 músicas mais tocadas em 2018. A ideia é escrever consultas SQL para responder perguntas específicas sobre essas músicas e seus artistas. 🚀

🗂 Estrutura de Arquivos
graphql
Copiar
Editar
📁 songs/
├── songs.db         # Banco de dados SQLite com as músicas
├── 1.sql            # Consulta 1: Lista de todas as músicas
├── 2.sql            # Consulta 2: Músicas em ordem crescente de ritmo
├── 3.sql            # Consulta 3: Top 5 músicas mais longas
├── 4.sql            # Consulta 4: Músicas dançantes, energéticas e felizes
├── 5.sql            # Consulta 5: Energia média das músicas
├── 6.sql            # Consulta 6: Músicas de Post Malone
├── 7.sql            # Consulta 7: Energia média das músicas de Drake
└── 8.sql            # Consulta 8: Músicas com participação (feat)
🛠 Passo a Passo
1️⃣ Crie o diretório de trabalho:

bash
Copiar
Editar
mkdir pset7
cd pset7
2️⃣ Baixe e extraia os arquivos do exercício:

bash
Copiar
Editar
wget https://cdn.cs50.net/2023/fall/psets/7/songs.zip
unzip songs.zip
rm songs.zip
cd songs
3️⃣ Verifique os arquivos:

bash
Copiar
Editar
ls
# Deve exibir: songs.db, 1.sql, 2.sql, ..., 8.sql
4️⃣ Explore o banco de dados:

bash
Copiar
Editar
sqlite3 songs.db
.schema  # Veja a estrutura das tabelas
📝 Consultas
1️⃣ 1.sql
🔍 Lista o nome de todas as músicas.

2️⃣ 2.sql
⬆️ Lista os nomes das músicas em ordem crescente de ritmo.

3️⃣ 3.sql
🏅 Lista os 5 nomes das músicas mais longas.

4️⃣ 4.sql
💃 Lista músicas com dançabilidade, energia e valência > 0,75.

5️⃣ 5.sql
⚡ Mostra a energia média de todas as músicas.

6️⃣ 6.sql
🎤 Lista músicas de Post Malone.

7️⃣ 7.sql
🔋 Retorna a energia média das músicas de Drake.

8️⃣ 8.sql
🤝 Lista músicas com participações especiais (contendo "feat").

✅ Teste Seu Código
Use o comando abaixo para validar suas soluções com o check50:

bash
Copiar
Editar
check50 cs50/problems/2024/x/songs
💡 Dicas Rápidas
Use SELECT para buscar dados.

Use ORDER BY para ordenar resultados.

Use LIMIT para restringir a quantidade de resultados.

Use LIKE '%feat.%' para buscar músicas com participação.

✨ Créditos
Desafio proposto por CS50.
