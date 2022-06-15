# fullstack_b7

# Teste para vaga de Fullstack Jr

O objetivo deste teste é entender o candidato, sua experiência e sua capacidade de resolução de problemas com dúvidas e detalhes que serão exigidos no dia-a-dia como programador Fullstack Junior.
O teste é baseado em questionamentos e problemas a serem resolvidos.

### Como será feito o teste?
O teste é dividido em 2 etapas:
- Questões teóricas.
- Projeto prático, quer seja correção de bug ou criação do mesmo.

O candidato precisa criar um repositório próprio com a seguinte estrutura:
- No README serão respondidas as questões teóricas (pergunta e resposta), de forma organizada e explicada.
- No próprio repositório estará o projeto prático, corrigido e/ou criado.

Após a finalização, o candidato deve enviar um e-mail para suporte@b7web.com.br com o link do repositório original (este) bem como o link do repositório pessoal com a resolução.

## Questões Teóricas

1. Quais as partes principais de uma requisição HTTP?
   get , post , put, patch , delete.

2. Qual a diferença entre colocar um script dentro do "head" e no fim do "body"?
   o head é a confiração da pagina e body é o corpo.

3. Qual a diferença entre display: block e display: inline-block ?
   o block um embaixo do outro o  incline é em linha.
   
4. É possível criar um site responsivo SEM media queries? Por que?
   não é possivel poque o media query ele que dar o limite que o browser vai e ate onde quando passa o linha tem uma quebra de linha.

5. No Javascript, é obrigatório usar VAR para criar uma variável?
   não é obrigatoria o com o javascript moderno utiliza a let por conta do hosting .

6. Criar funções com "function() {}" e com "() => {}" tem alguma diferença além da sintaxe?
   não tem diferença o arrow faction ele ajuda na questao de escrever menos codigo.

7. Explique a lógica pra fazer uma paginação.
   document.querySelector('').style.background='red';
    
8. Qual a melhor forma de armazenar uma imagem no banco de dados?
   com linha de comando como essa  Select * from fotos_festa; 

9. No React, quantos useEffect eu posso usar?
O useEffectGancho permite que você execute efeitos colaterais em seus componentes.

10. Quais métodos de requisição preciso para criar um CRUD via API?
  get , post , put , delete.

## Projeto prático

Crie uma aplicação do tipo BLOCO DE NOTAS em React. Essa aplicação deve fazer:
- Adicionar uma nova nota.
- Editar uma nota existente.
- Deletar uma nota.
- Na listagem, cada nota deve ter uma cor própria de fundo, escolhida de uma lista de cores predefinidas na página de adicionar/editar.

Toda a aplicação deve funcionar via API, com o backend criado por você.
A beleza estética do design não irá influenciar, contudo, a organização da estrutura de interface sim será observada.

Tanto o BACKEND quanto o FRONTEND devem fazer uso de variáveis de ambiente.

No backend, a criação e uso de migration é um plus mas não é obrigatório. Caso não use migration, colocar um arquivo .txt com a estrutura de banco de dados para replicação.
