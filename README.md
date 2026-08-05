# Trama — BNCC Computação

Portal estático para planejamento interdisciplinar, avaliação por rubricas e acompanhamento pedagógico com identificadores numéricos.

## Recursos

- geração de planos com tecnologia e sem tecnologia;
- correspondências entre componentes curriculares e BNCC Computação;
- catálogo pesquisável de Computação do 6º ao 9º ano;
- 570 habilidades oficiais de Matemática, Língua Portuguesa, Ciências, Geografia, História e Arte;
- sugestão de projetos transversais;
- cadastro de turmas usando apenas números;
- avaliação em cinco dimensões;
- relatórios individuais imprimíveis;
- PDI pedagógico sem dados clínicos;
- backup e restauração em arquivo JSON;
- funcionamento offline após o primeiro acesso.

## Privacidade

Todos os registros ficam no armazenamento local do navegador. O portal não envia dados de turmas, avaliações ou PDIs para o GitHub.

## Publicação

O workflow em `.github/workflows/pages.yml` publica o conteúdo estático no GitHub Pages quando a branch `main` é enviada ao GitHub. Nas configurações do repositório, selecione **GitHub Actions** como origem do Pages.

## Uso local

Sirva a pasta com qualquer servidor HTTP estático. Abrir o `index.html` diretamente também permite testar a maior parte dos recursos, mas o modo offline requer HTTP.
