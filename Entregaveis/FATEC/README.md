# Versionamento

| Versão | Descrição |
| ------ | --------- |
| 0.1.0 | Criação do documento, com adição de introdução, objetivos e documentação do escopo. |
| 0.1.1 | Removidos exemplos da documentação principal. |
| 0.1.2 | Adicionada tabela de versionamento. |
| 0.1.3 | Expandida seção de escopo e adicionadas seções 1.5 e 2.* |
| 0.1.4 | Integrados diagramas com a documentação do *SRS* na seção 1.6 |
| 0.1.5 | Iniciada conversão do *SRS* de *word* para *markdown*, transcrevendo toda a seção 1.* |
| 0.1.6 | Transcrita a seção 2.1.* para *markdown*, também iniciada a documentação da sessão 2.2.* |
| 0.1.7 | Ampliada seção de discussão sobre interface do usuário e verificações de coesão pelo texto |
| 0.1.8 | Feita verificação e correção ortográfica na documentação |
| 0.1.9 | Feita verificação e correção de sintaxe Markdown na documentação |

# Documento de especificação de requisitos

## 1.Introdução
Na sociedade atual, crianças renegadas pela família ou que a perde são enviadas para orfanatos, onde o estado lhe fornece condições de vida e tudo que o estatuto da criança e do adolescente garante a eles. Todavia, quando essas crianças completam a maioridade, são simplesmente despejadas desse lugar e postas no mundo para que vivam sozinhas a partir dali, não havendo nenhum tipo de auxílio governamental, este é o problema que nosso projeto visa resolver. <br>
Com a pandemia da Sars-CoV-2 (Covid-19), esta adversidade foi intensificada devido ao fato das famílias estarem sendo dizimadas pela doença, fato que resulta em deixar menores de idade por muitas vezes sozinhos. A sociedade e o governo fecham os olhos para essas pessoas após completarem dezoito anos. Sem assistência, eles passam a viver com o que lhes é fornecido, como por exemplo, usufruindo de drogas, adentrando ao mundo da prostituição ou tornando-se andarilhos. <br>

### 1.1. Objetivo
Auxiliar os jovens recém desabrigados com empregos e moradia, sendo possível através de parcerias entre os organizadores desse projeto, voluntários, orfanatos e empresas que estejam dispostas a oferecerem as vagas de emprego. <br>

### 1.2 Escopo
- O projeto receberá formulários *online* de orfanatos que cadastrarão os órfãos que completarão a maioridade em breve.
- Haverá também os cadastros independentes, onde pessoas em situações parecidas aos órfãos, porém que não frequentaram orfanatos, poderão se inscrever.
- No *site* terá inscrições para voluntários, os quais ajudarão a manter a moradia organizada e em ordem.
- Semanalmente serão enviadas pessoas de nossa confiança e de confiança das empresas patrocinadoras para verificar a situação de vivência e do local.

### 1.3 Bibliografia de pesquisa
- Paraná Governo do estado, acessado em 17/04/2021: http://www.justica.pr.gov.br/Noticia/Criancas-que-perderam-os-pais-durante-pandemia-da-COVID-19-terao-apoio-da-Secretaria-de
- El país, acessado em 17/04/2021: https://brasil.elpais.com/brasil/2021-03-04/como-se-viram-as-familias-com-orfaos-da-covid-19.html
- Lunetas, acessado em 17/04/2021: https://lunetas.com.br/orfaos-da-pandemia/
- Cultura UOL, acessado em 26/04/2021: https://cultura.uol.com.br/noticias/19050_covid-19-pandemia-faz-crescer-numero-de-criancas-e-adolescentes-orfaos.html
- Senado notícias, acessado em 26/04/2021: https://www12.senado.leg.br/noticias/materias/2020/05/22/jovens-nao-adotados-vivem-drama-quando-fazem-18-anos-e-precisam-deixar-abrigos

### 1.4 Visão geral
- Haverá auxílio para esses jovens no quesito mercado de trabalho como palestras, cursos profissionalizantes, além de termos contratos pré-determinados com empresas para estar recolocando esses jovens no mercado de trabalho.
- O nosso projeto está organizado como um *site* de auxílio e ajuda para cadastros de jovens abandonados pelas suas respectivas famílias, empresas cadastradas em nosso *site* que estão visando fornecer assistência para a reinserção desses jovens em um mercado de trabalho. Teremos o cadastro de voluntários para pessoas que simpatizam com a causa e querem prestar um apoio a esses jovens.

### 1.5 Interações entre o usuário e o sistema
As interações dos usuários com o sistema se dão de maneira superficial desde quando este acessa o *site* de apresentação do sistema até o uso das funcionalidades mais restritas em si. Essa seção aborda os casos de uso e fluxos pelos quais o usuário passa ao se aprofundar pelo sistema. <br>

#### 1.5.1 Cadastro
O futuro usuário entrará nas áreas restritas do sistema a partir do cadastro de uma conta, essa que passará pela aprovação de um ou mais membros do corpo de gerência, conforme mostra o seguinte caso de uso: <br>
![Diagrama de caso de uso de cadastro](https://user-images.githubusercontent.com/51335343/120077562-57209780-c081-11eb-83bb-5a2c20236c15.png)

O usuário acessará a página responsável pelo cadastro de contas, o mesmo irá selecionar o tipo de perfil que será criado (órfão, voluntário ou empresa). Após esse preenchimento, o usuário deve concordar com os termos de uso para prosseguir com a parte final do cadastro. Posteriormente, serão requisitados os documentos do mesmo, que deverão ser anexados na plataforma. Caso alguma etapa dê errado uma mensagem de erro aparecerá e o cadastro não será efetivado. <br>
![Diagrama de atividades de cadastro](https://user-images.githubusercontent.com/51335343/120077581-73243900-c081-11eb-9ab2-7833b58e10f0.png)

##### 1.5.1.1 Especialização de usuários
O orfanato pode realizar o cadastro dos jovens no sistema e/ou realizar a candidatura do mesmo para a vaga. Já o voluntário realiza o cadastro no sistema, escolhe se prefere fiscalizar as moradias onde os jovens estão alocados ou averiguar a situação de trabalho onde estes foram contratados. Em futuras atualizações do sistema, os voluntários também vão ter disponível, uma funcionalidade para a criação de relatórios sobre as condições de moradia e emprego que foram oferecidas aos jovens. <br>
![Diagrama de caso de uso no cadastro pelo orfanato](https://user-images.githubusercontent.com/51335343/120077687-05c4d800-c082-11eb-9575-66bbba0f734d.png)
![Diagrama de caso de uso no cadastro pelo voluntário](https://user-images.githubusercontent.com/51335343/120077706-16754e00-c082-11eb-9c24-a8063d951243.png)

##### 1.5.1.2 Aprovação do cadastro do usuário
Após o envio dos cadastros é necessário que a gerência aprove ou desaprove a solicitação. Para isso verifica-se os documentos enviados, os quais comprovam que a pessoa é apta para participar do programa, posteriormente agendam ou não uma reunião com o indivíduo. Independentemente do resultado, é enviado um *email* para a conta do solicitante, o qual lhe fornecerá o resultado. <br>
![Diagrama de atividades de aprovação do cadastro](https://user-images.githubusercontent.com/51335343/120077598-8c2cea00-c081-11eb-8b41-efa11ba5fe27.png)

#### 1.5.2 Vagas de emprego
Após a aprovação do cadastro, o usuário poderá se candidatar as vagas e a empresa poderá solicitar anúncios para vagas, com a aprovação dessas solicitações ficando pendente mediante análise da gerência. <br>
![Diagrama de caso de uso das vagas](https://user-images.githubusercontent.com/51335343/120077649-cc8c6800-c081-11eb-8eb3-8b5ffe4defda.png)

Quando o usuário utilizar as principais funções do sistema, como candidatar-se a vagas ou anunciá-las, ocorrerá uma verificação a respeito da validação do perfil, se há um cadastro do mesmo para permitir o acesso, dentro dessa verificação o sistema buscará o nível do usuário que varia de padrão até entidade colaboradora/empresa para liberar as informações de acordo, podendo assim realizar candidaturas ou anunciar oportunidades de emprego. <br>
![Diagrama de atividades de cadastro de vagas](https://user-images.githubusercontent.com/51335343/120077663-e4fc8280-c081-11eb-8361-bd5d62efe43d.png)

## 2. Descrição geral

### 2.1. Requisitos funcionais
Os requisitos do sistema podem atualmente ser descritos como atuais, que devem estar presentes na versão inicial, bem como futuros, que podem ser preenchidos em futuras versões do *software*. <br>

#### 2.1.1. Requisitos atuais
- Formulário *online*;
- Cadastro de usuários com múltiplas  possibilidades de perfil, como órfãos, voluntários ou empresas;
- Análise e aprovação ou negação dos cadastros;
- Gerência do projeto e empresas anunciarem vagas de emprego.

#### 2.1.2. Requisitos futuros
- Relatórios de verificação da vivência dos jovens, feitos pelos voluntários;

### 2.2. Interface de usuário
A solução será uma aplicação *web* responsiva que poderá ser acessada de qualquer sistema operacional, seja *desktop* ou *mobile*, desde que tenha um navegador e esteja conectado a *internet*. O intuito é que o sistema seja facilmente acessível por pessoas nas mais variadas condições e realidades sociais. <br>

#### 2.2.1. A construção da *UI*
A interface do sistema se inspira em um *design* leve e aconchegante aos olhos, utilizando-se de um esquema de cores neutras e calmas, como tons de cinza e ciano, aliados a um novo clássico - a utilização de *cards* para a construção dos componentes de forma simples e minimalista. <br>

![Tela de vagas de emprego disponíveis](https://user-images.githubusercontent.com/51335343/120252956-74f62400-c25c-11eb-8789-11751f8ea4b4.png)

Atualmente em fase de prototipagem, o sistema está sendo construído e mantido na ferramenta de edição vetorial Figma, [nesse *design*](https://www.figma.com/file/EKzpBET8KKNqowKngOFdKR/Wireframe-sistema?node-id=0%3A1), com esses desenhos e esboços sendo arquitetados seguindo um princípio de componentização do *frontend*, no qual elementos que se repetem são criados uma única vez e replicados pelas telas, conforme pode ser visto na árvore de componentes exposta pela figura abaixo. <br>


![Estrutura de componentes](https://user-images.githubusercontent.com/51335343/120253007-9d7e1e00-c25c-11eb-853d-0e0f1f41fd19.png)

## 2.3 Limites do sistema

### 2.3.1 Interação entre órfão e empresa
A plataforma irá monitorar os órfãos recrutados através de pessoas de confiança que irão visitá-los periodicamente, garantindo assim a maior confiança por parte do órfão e os Direitos Humanos de cada indivíduo. <br>

### 2.3.2 Interação entre empresa e voluntário
O sistema cobrirá a parte de parceria das duas entidades (empresa e voluntário), servindo como uma vitrine para ambos, visando facilitar o contato. <br>
Porém, todas as responsabilidades informacionais, comunicativas e principalmente legais, recaem unicamente e exclusivamente a quem o fizer, seja empresa ou voluntário. <br>

## 2.4 Responsabilidades Legais

### 2.4.1 Empresas parceiras
É de responsabilidade total da empresa parceira todo o processo de comunicação feita através da plataforma, bem como qualquer acordo feito com os usuários e/ou voluntários. <br>

### 2.4.2 Voluntários
É de responsabilidade total do voluntário todo o processo de comunicação, acordos e doações feitos em parceria com as empresas para ajudar os órfãos <br>

### 2.4.3 Gerência e desenvolvedores do sistema
É de responsabilidade total da gerência do sistema o gerenciamento das informações contidas no sistema, tais como: vagas, órfãos, voluntários e patrocinadores. <br>

### 2.4.3 Órfãos
É de responsabilidade total dos órfãos a legibilidade e autenticidade dos documentos e informações fornecidos no momento do cadastro. <br>




