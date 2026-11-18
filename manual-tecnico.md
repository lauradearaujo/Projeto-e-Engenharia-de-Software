# Manual Técnico
4. Manual Técnico e Manutenção

SOS Hospitalar | Engenharia de Software

Objetivo

Este manual tem como objetivo orientar a continuidade do projeto SOS Hospitalar, desde a organização dos arquivos até o controle de versões e os cuidados necessários para a manutenção da solução.

Atualmente, o projeto possui um protótipo navegável. Portanto, banco de dados, servidor e serviços em produção não devem ser considerados implementados sem comprovação.

⸻

4.1 Organização técnica dos arquivos

Para manter o projeto organizado e facilitar a colaboração entre os integrantes, recomenda-se a seguinte estrutura de diretórios no GitHub:

Arquivo/Pasta	Finalidade
README.md	Apresentação do projeto, instruções e links de acesso.
docs/	Visão geral, requisitos, diagramas, arquitetura e possíveis registros de manutenção.
manuais/	Manual do usuário e este manual técnico (manual-tecnico.md).
pitch/	Apresentação da proposta e Canvas.
prototipo/	Link do protótipo e imagens das telas.

Observação: essa é uma estrutura sugerida pelo grupo. Antes de realizar alterações, é importante confirmar os nomes e conteúdos que já existem no repositório.

4.2 Acesso e versionamento pelo GitHub

O GitHub será utilizado para armazenar os arquivos do projeto, acompanhar as alterações e facilitar o trabalho colaborativo entre os integrantes.

O fluxo de trabalho recomendado é:

1. Acessar o repositório do SOS Hospitalar.
2. Obter os arquivos pela opção Code, realizando o download ou a clonagem do repositório.
3. Criar uma branch própria para trabalhar nas alterações.
4. Atualizar a branch principal (main) antes de iniciar.
5. Registrar as modificações por meio de commits.
6. Enviar a branch para o GitHub.
7. Abrir um Pull Request para que outro integrante revise as alterações.
8. Integrar as modificações à main somente após a aprovação.

Exemplo de fluxo básico de comandos:

git switch main
git pull
git switch -c manual-tecnico
# Editar os arquivos necessários
git add .
git commit -m "Atualiza manual técnico"
git push

Após o envio, deve ser aberto um Pull Request no GitHub para revisão e integração das alterações.

4.3 Tipos de manutenção

A manutenção do SOS Hospitalar pode ser dividida em três categorias principais:

Manutenção corretiva

Consiste em resolver falhas identificadas no sistema ou na documentação, como links quebrados, telas com erros ou instruções incorretas.

O procedimento deve incluir:

* Identificação e registro do problema.
* Correção da falha.
* Realização de testes.
* Revisão da alteração antes da publicação.

Manutenção preventiva

Tem como objetivo evitar problemas futuros por meio de verificações periódicas.

Alguns cuidados importantes são:

* Conferir regularmente as telas e os links.
* Revisar a documentação.
* Verificar o acesso aos arquivos.
* Manter cópias de segurança para evitar a perda de informações.

Manutenção adaptativa

Consiste em atualizar o projeto quando houver mudanças nos processos hospitalares ou nas ferramentas utilizadas.

Pode envolver:

* Atualização dos fluxos de atendimento.
* Revisão dos requisitos.
* Atualização dos diagramas.
* Modificação dos manuais e demais documentos.

4.4 Infraestrutura e continuidade

Na fase atual do projeto, é importante preservar o link do protótipo, os arquivos, as imagens e o histórico de alterações armazenados no GitHub.

Para uma futura implantação do sistema, será necessário planejar:

* Hospedagem: definir onde o sistema será disponibilizado.
* Disponibilidade: planejar mecanismos para manter o serviço acessível.
* Controle de acesso: estabelecer permissões de acordo com os perfis dos usuários.
* Proteção de dados: garantir a segurança das informações dos pacientes.
* Backups: realizar cópias de segurança e testar sua restauração.
* Atualizações de segurança: manter os componentes utilizados atualizados.
* Monitoramento: acompanhar possíveis falhas e problemas de funcionamento.

Atenção: nunca registrar senhas ou dados reais de pacientes no repositório do GitHub.

4.5 Estimativas de custos

O planejamento inicial do SOS Hospitalar apresenta as seguintes estimativas:

Categoria	Custo estimado
Desenvolvimento	R$ 20.000 a R$ 60.000
Implantação e treinamento	R$ 5.000 a R$ 15.000
Infraestrutura e manutenção	R$ 1.000 a R$ 3.000 por mês

Observação: os valores apresentados são estimativas preliminares do planejamento, não despesas já realizadas. Eles deverão ser revisados antes de uma possível implantação, considerando o tamanho da equipe, os serviços de hospedagem, o suporte necessário e a escala do sistema.

SOS Hospitalar | Engenharia de Software
Manual Técnico e Manutenção
