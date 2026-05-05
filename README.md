# 🚗 Rodízio SP App

Política de Privacidade e Proteção de Dados

Última atualização: 5 de maio de 2026

### ⚠️ Aplicativo Não Oficial

**Este é um aplicativo não oficial e criado de forma independente.** Não é desenvolvido, mantido ou endossado pela Prefeitura de São Paulo, pela CET (Companhia de Engenharia de Tráfego) ou por qualquer órgão governamental municipal.

**As regras do rodízio podem ser alteradas ou suspensas pela Prefeitura de São Paulo em feriados, datas especiais ou por decisão operacional.** Sempre consulte a fonte oficial antes de tomar decisões importantes de deslocamento: [https://www.cetsp.com.br/rodizio.aspx](https://www.cetsp.com.br/rodizio.aspx)

### 📑 Sumário

- [Introdução](#introducao)
- [Dados Coletados](#dados-coletados)
- [Armazenamento de Dados](#armazenamento)
- [Notificações e Permissões](#notificacoes)
- [Segurança](#seguranca)
- [Seus Direitos (LGPD)](#direitos-lgpd)
- [Compartilhamento de Dados](#compartilhamento)
- [Menores de Idade](#menores)
- [Alterações](#alteracoes)
- [Contato](#contato)

## 1\. Introdução

O **Rodízio SP App** é um aplicativo mobile desenvolvido de forma independente para ajudar motoristas a monitorarem o rodízio de veículos em São Paulo. Esta política de privacidade explica como coletamos, usamos, armazenamos e protegemos seus dados pessoais.

Este aplicativo foi desenvolvido em conformidade com:

- **Lei Geral de Proteção de Dados (LGPD)** - Lei Nº 13.709/2018 (Brasil)
- **Diretrizes de Privacidade do Google Play Store**
- **Diretrizes de Privacidade da Apple App Store**
- **Boas práticas de segurança de dados**

Ao usar este aplicativo, você concorda com as práticas descritas nesta política. Se você não concordar com nossas práticas de privacidade, por favor, não use o aplicativo.

## 2\. Dados Coletados

#### ✓ Abordagem Local-First

O Rodízio SP App foi desenvolvido com uma filosofia **Local-First**, o que significa que todos os seus dados são armazenados **exclusivamente em seu dispositivo**. Não mantemos servidores backend que coletam ou processam seus dados pessoais.

### 2.1 Dados que Coletamos

O aplicativo coleta e armazena **apenas localmente** os seguintes dados:

- **Nome do veículo:** Um identificador customizado que você atribui (ex: "Celta vermelho")
- **Cor do veículo:** Cor selecionada para identificação visual
- **Último dígito da placa:** Número de 0 a 9 para determinar o rodízio
- **Data de criação:** Timestamp do cadastro do veículo
- **Configurações de notificação:** Horários de alerta (manhã e tarde) e preferências de ativação

### 2.2 Dados que NÃO Coletamos

**O aplicativo NÃO coleta:**

- Dados de geolocalização
- Histórico de navegação ou movimento
- Informações de identificação pessoal (CPF, RG, etc.)
- Dados de email, telefone ou redes sociais
- Dados biométricos
- Informações financeiras ou de cartão de crédito
- Número completo da placa do veículo
- Dados de comportamento de uso detalhados
- Analytics ou telemetria (sem Google Analytics, Firebase ou similares)

**💡 Privacidade por Padrão:** Nenhuma funcionalidade do aplicativo depende da coleta de dados pessoais adicionais. Todas as features funcionam localmente no seu dispositivo.

## 3\. Armazenamento de Dados

### 3.1 Armazenamento Local

Todos os seus dados são armazenados **exclusivamente no seu dispositivo** usando o mecanismo nativo de armazenamento:

- **Android:** Utiliza a API `SharedPreferences` através da biblioteca `@react-native-async-storage`
- **iOS:** Utiliza `NSUserDefaults` através da biblioteca `@react-native-async-storage`

Estes dados são armazenados em uma área de dados privada da aplicação que apenas o Rodízio SP App pode acessar.

### 3.2 Nenhum Envio para Servidores

**Seus dados nunca são enviados para nenhum servidor externo**. O aplicativo funciona completamente offline após a instalação. Não há sincronização com clouds, não há backup automático online, não há coleta de dados em servidores.

#### ⏱️ Retenção de Dados

**Duração:** Os dados são mantidos no seu dispositivo enquanto o aplicativo estiver instalado.

**Exclusão:** Todos os dados são automaticamente deletados quando você:

- Desinstala o aplicativo
- Limpa os dados/cache do aplicativo nas configurações do sistema operacional
- Executa um reset de fábrica do dispositivo
- Manualmente remove um veículo através da interface do app

### 3.3 Backup de Dados

Dependendo das configurações do seu dispositivo, o sistema operacional pode realizar backups automáticos:

- **Android:** Se você ativou o backup automático do Google, os dados do app podem ser incluídos
- **iOS:** Se você ativou o iCloud backup, os dados do app podem ser incluídos

Você pode desativar esses backups automáticos através das configurações do seu dispositivo. O Rodízio SP App não oferece backup de dados específico.

## 4\. Notificações e Permissões

### 4.1 Notificações Locais

O aplicativo utiliza **notificações locais** para alertar você sobre períodos de rodízio. Estas notificações:

- São agendadas **localmente no seu dispositivo**
- Não dependem de servidores externos
- Não enviam dados para nenhum servidor
- São baseadas nas configurações que você define no app

### 4.2 Permissões Solicitadas

| Permissão              | Plataforma  | Uso                                                      |
| ---------------------- | ----------- | -------------------------------------------------------- |
| **POST_NOTIFICATIONS** | Android 13+ | Exibir notificações locais de rodízio no seu dispositivo |
| **Notificações**       | iOS         | Exibir notificações locais de rodízio no seu dispositivo |

### 4.3 Controle de Permissões

Você pode ativar ou desativar notificações a qualquer momento:

- Através das configurações dentro do aplicativo (toggle por período)
- Através das configurações gerais do seu sistema operacional
- Negando a permissão quando o app solicita

Se você negar a permissão de notificações, o app funcionará normalmente, você apenas não receberá alertas automáticos.

#### ℹ️ Sem Rastreamento

As notificações não são rastreadas. Não enviamos informações sobre quando você vê, interage ou ignora uma notificação para nenhum servidor.

## 5\. Segurança de Dados

### 5.1 Medidas de Segurança

Como o Rodízio SP App é local-first, a segurança dos seus dados depende principalmente de:

- **Segurança do dispositivo:** Proteja seu smartphone com senha/biometria
- **Isolamento do aplicativo:** Os dados são armazenados em área privada que outros apps não acessam
- **Não há transmissão de dados:** Elimina riscos de interceptação em trânsito

### 5.2 Segurança de Dados em Trânsito

Como o aplicativo não faz nenhuma chamada de rede, não há dados transmitidos pela internet. Portanto, não há riscos de interceptação de dados em trânsito.

### 5.3 Segurança do Código

O código do Rodízio SP foi desenvolvido seguindo rigorosas práticas de segurança de dados. As funcionalidades foram projetadas com foco em proteção de privacidade desde o início.

### 5.4 Limitações de Responsabilidade

Nós não podemos ser responsáveis por:

- Acesso não autorizado ao seu dispositivo
- Malware ou software malicioso no seu dispositivo
- Perda de dados devido a dano físico do dispositivo
- Exclusão acidental de dados pelo usuário
- Falhas de segurança do sistema operacional (Android/iOS)

## 6\. Seus Direitos sob a LGPD (Lei Geral de Proteção de Dados)

#### O que é a LGPD?

A Lei Geral de Proteção de Dados (LGPD - Lei Nº 13.709/2018) é a legislação brasileira que regulamenta o tratamento de dados pessoais e garante direitos aos cidadãos. O Rodízio SP App respeita plenamente todos os direitos garantidos pela LGPD.

### 6.1 Seus Direitos

Como usuário do Rodízio SP App, você tem os seguintes direitos, conforme a LGPD:

#### ✓ Direito de Acesso

Você pode acessar todos os seus dados a qualquer momento. Os dados são claramente visíveis na interface do aplicativo (lista de veículos, configurações de notificação, etc.).

#### ✓ Direito de Retificação

Você pode corrigir ou atualizar seus dados a qualquer momento através da interface do app (editar nome, cor e dígito do veículo).

#### ✓ Direito de Exclusão ("Direito ao Esquecimento")

Você pode excluir qualquer veículo ou todos os seus dados do aplicativo a qualquer momento:

- Deletando veículos individuais através da interface do app
- Limpando dados do aplicativo nas configurações do sistema operacional
- Desinstalando o aplicativo completamente

#### ✓ Direito à Portabilidade de Dados

Seus dados são seus. Como estão armazenados localmente no seu dispositivo, você tem total controle sobre eles. Você pode extraí-los e transferi-los conforme necessário (através do backup do dispositivo).

#### ✓ Direito de Oposição

Você pode se opor a qualquer prática de processamento de dados. Como não processamos dados em servidores e não fazemos coleta não consentida, este direito é respeitado por padrão.

#### ✓ Direito à Não Discriminação

Você não sofrerá discriminação por exercer qualquer dos seus direitos LGPD. O funcionamento completo do app não depende da coleta de dados pessoais.

### 6.2 Como Exercer Seus Direitos

**Você pode exercer seus direitos LGPD através de:**

- **Diretamente no app:** A maioria dos direitos pode ser exercida através da interface do aplicativo (editar, deletar dados)
- **Contato por email:** Para solicitações formais, você pode nos contatar no endereço de email fornecido na seção de contato

### 6.3 Prazos de Resposta

Conforme a LGPD, o prazo máximo para responder a solicitações de exercício de direitos é de **15 dias**, prorrogáveis por mais 15 dias em situações complexas.

## 7\. Compartilhamento de Dados

### 7.1 Compartilhamento Interno

**Seus dados não são compartilhados com terceiros.** Como o aplicativo é local-first, não há compartilhamento de dados com:

- Servidores backend
- Serviços de análise (Google Analytics, Firebase, etc.)
- Redes de publicidade
- Plataformas de redes sociais
- Órgãos governamentais (exceto conforme exigido por lei)
- Fornecedores de serviços em nuvem

### 7.2 Compartilhamento Obrigado por Lei

Nós podemos ser obrigados a compartilhar seus dados se:

- Exigido por ordem judicial
- Exigido por autoridades governamentais legalmente competentes
- Necessário para cumprir a lei ou regulação aplicável

Neste caso, qualquer compartilhamento será feito conforme exigido pela lei e nossos esforços serão feitos para notificá-lo quando legalmente permitido.

### 7.3 Compartilhamento com Dependências de Código

O aplicativo utiliza bibliotecas externas de terceiros. Nenhuma dessas dependências acessa ou transmite seus dados pessoais. Todas as bibliotecas foram selecionadas com cuidado para garantir que não coletam ou rastreiam dados do usuário.

## 8\. Proteção de Menores de Idade

### 8.1 Consentimento dos Responsáveis

O Rodízio SP App não é intencionalmente direcionado a menores de idade (menores de 18 anos). Se você é menor de idade:

- Você deve obter consentimento de seus pais ou responsáveis legais antes de usar o app
- Ao usar o app, você concorda que tem essa autorização

### 8.2 Proteção de Dados de Menores

Como não coletamos dados pessoais sensíveis além do que é estritamente necessário para a funcionalidade do app, a privacidade de menores é protegida por padrão.

### 8.3 Descoberta de Uso por Menores

Se descobrirmos que um menor de idade está usando o app sem consentimento dos responsáveis, tomaremos as medidas apropriadas conforme a LGPD e legislação aplicável.

## 9\. Alterações na Política de Privacidade

Nós podemos atualizar esta política de privacidade de tempos em tempos para refletir mudanças em nossas práticas, tecnologia, legislação e outros fatores.

### 9.1 Como Serão Notificadas as Alterações

**Notificação de alterações materiais:**

- Se fizermos alterações materiais (que afetam significativamente seus direitos), atualizaremos a data "Última atualização" no topo deste documento
- Mudanças significativas podem ser comunicadas através de:
  - Aviso no aplicativo
  - Atualizações de versão do app

### 9.2 Seu Consentimento com Alterações

Seu uso continuado do aplicativo após publicação de alterações significa que você concorda com a política revisada. Se você não concordar com as alterações, você deve parar de usar o aplicativo.

### 9.3 Histórico de Alterações

| Data              | Versão | Alteração                                     |
| ----------------- | ------ | --------------------------------------------- |
| 5 de maio de 2026 | 1.0.0  | Publicação inicial da Política de Privacidade |

## 10\. Contato e Dúvidas

Se você tiver dúvidas, preocupações ou desejar exercer qualquer de seus direitos conforme esta política de privacidade ou a LGPD, por favor entre em contato conosco:

### 📞 Informações de Contato

**📧 Email:** [victoroliveira.sde@gmail.com](mailto:victoroliveira.sde@gmail.com)

**📝 Como Entrar em Contato:**

- Descreva sua questão ou solicitação de forma clara
- Forneça informações suficientes para que possamos identificar sua solicitação
- Especifique qual direito LGPD você deseja exercer (se aplicável)

### 10.1 Tempo de Resposta

Nós nos comprometemos a responder a todas as solicitações de privacidade em até **7 dias úteis**, conforme prazo máximo de 15 dias estabelecido pela LGPD.

### 10.2 Denúncia a Órgãos Reguladores

Se você acreditar que seus direitos LGPD foram violados e não conseguir resolver a questão conosco, você tem o direito de fazer uma denúncia à:

- **Autoridade Nacional de Proteção de Dados (ANPD)** [Site oficial](https://www.gov.br/cidadania/pt-br/acesso-a-informacao/lgpd)

## Isenção de Responsabilidade

**Aviso Importante:** Este aplicativo é fornecido "como está" sem garantias. Nós não garantimos que o aplicativo funcionará sem interrupções ou que será livre de erros.

As informações fornecidas pelo aplicativo sobre rodízio são baseadas nas regras conhecidas e podem não estar sempre atualizadas. **Sempre consulte a fonte oficial** (CET - Companhia de Engenharia de Tráfego) antes de tomar decisões importantes sobre deslocamento: [https://www.cetsp.com.br/rodizio.aspx](https://www.cetsp.com.br/rodizio.aspx)

Nós não somos responsáveis por multas, infrações de trânsito ou outros danos resultantes do uso ou mal uso deste aplicativo.

© 2026 Rodízio SP App

📱 **Aplicativo versão:** 1.0.0
📄 **Política versão:** 1.0
📅 **Última atualização:** 5 de maio de 2026

**Nota:** Esta política é disponibilizada em Português Brasileiro. Em caso de conflito entre versões em diferentes idiomas, a versão em Português Brasileiro prevalece.
