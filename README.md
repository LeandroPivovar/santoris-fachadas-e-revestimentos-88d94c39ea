# Santoris Fachadas e Revestimentos

Site institucional baseado no segundo print fornecido: abertura com quatro fotografias verticais escalonadas, navegação arredondada, blocos claros, serviços, referências, contato e FAQ. Identidade adaptada para verde e dourado da Santoris.

## Arquivos e execução

Conteúdo público em `dist/`. Site estático sem dependências ou etapa de build. Sirva essa pasta em um servidor estático; imagens e fontes estão locais.

O formulário prepara a mensagem com assunto, cidade e projeto para o WhatsApp confirmado (42) 99808-3926. O visitante revisa e envia; nenhum campo é armazenado pelo site. Os botões de serviços preenchem o assunto. A galeria tem filtros acessíveis e o FAQ usa controles nativos expansíveis.

## Dados e imagens

Informações fornecidas: 25 anos de trajetória; fachadas e revestimentos; soluções em engenharia para projetos de todos os portes; atendimento nacional. O mapa do Brasil representa a área geral informada, sem sugerir sede ou endereço comercial. Disponibilidade por cidade é consultada diretamente.

Não há catálogo técnico, materiais específicos ou obras próprias confirmados. Imagens são referências ilustrativas, identificadas na página e no FAQ. Não foram inventadas equipes, clientes, resultados, certificações ou números de obras. Horário de terça-feira no print não foi generalizado para outros dias.

Créditos de fotografias e fontes em `dist/assets/credits.md`. O nome é apresentado como marca tipográfica até haver arquivo original do logotipo.

## Entrega

Commit e push no GitHub. Nenhum deploy é executado nesta entrega; `git.deploymentEnabled: false` impede deploys automáticos da integração Git da Vercel, seguindo a preferência expressa na conversa. A configuração de saída estática permanece pronta para futura hospedagem autorizada.

Metadados locais de CRM, arquivos de revisão e variáveis de ambiente não integram a saída pública nem os arquivos versionados.
