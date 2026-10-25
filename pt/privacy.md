---
title: Política de Privacidade do Habit Tracker
lang: pt
---

# Política de Privacidade do Habit Tracker: Game & Friends

*Esta é uma tradução. Se ela divergir da [versão em inglês](../privacy), prevalecerá a versão em inglês.*

Data de vigência: 2026-10-24

Esta política explica como o Habit Tracker: Game & Friends (exibido como "Hábitos" na sua Tela de Início, o "Aplicativo"), desenvolvido por Stanislau Malchanau ("nós"), trata suas informações. Em resumo: **não coletamos, não vendemos nem compartilhamos seus dados pessoais. Seus hábitos permanecem no seu dispositivo e na sua própria conta do iCloud.**

## 1. Dados que o Aplicativo armazena

O Aplicativo armazena o seguinte no seu dispositivo: seus hábitos (nome, ícone, cor, tipo, programação, meta e horários dos lembretes), suas marcações de cada dia, pausas e dias de descanso, sua vila (em qual terreno fica a casinha de cada hábito e quanto ela já cresceu) e seus ajustes. Seu Apple Watch guarda uma cópia dos mesmos dados para mostrar e marcar seus hábitos.

Não operamos servidores que recebam esses dados e não temos acesso a eles. As exceções são os horários de uma Atividade ao Vivo em andamento (seção 5) e os sinais de uso anônimos (seção 8).

## 2. Sincronização com o iCloud

Se você tiver iniciado sessão no iCloud, o Aplicativo sincroniza seus dados por meio do CloudKit da Apple, no banco de dados privado da sua própria conta do iCloud, para que seu iPhone, seu iPad e seu Apple Watch mostrem os mesmos hábitos. Esses dados são armazenados e protegidos pela Apple nos termos da Política de Privacidade da Apple (https://www.apple.com/legal/privacy/). Não podemos ver, ler nem exportar esses dados. Você pode desativar a sincronização em Ajustes do iOS > [seu nome] > iCloud.

## 3. Hábitos compartilhados com amigos

Você pode convidar amigos para um hábito compartilhado. Um hábito compartilhado fica em uma zona compartilhada da sua conta do iCloud por meio do compartilhamento do CloudKit da Apple. As pessoas que você convida, e somente elas, veem o nome, o ícone, a programação e as marcações desse hábito, além do nome que cada participante tem no iCloud. Seus outros hábitos nunca são compartilhados. Cada participante pode sair de um hábito compartilhado a qualquer momento, e quem o criou pode remover um participante ou parar de compartilhar; a partir daí, as cópias deles deixam de ser atualizadas. Não podemos ver os hábitos compartilhados nem quem participa deles.

## 4. Movimento dos fones de ouvido e som espacial

Com AirPods ou outros fones de ouvido compatíveis, o Aplicativo pode usar o movimento da sua cabeça para manter os sons da vila no lugar quando você se vira. Esses dados de movimento são processados no seu dispositivo em tempo real, nunca são armazenados e nunca saem do seu dispositivo.

## 5. Notificações, Atividade ao Vivo e widgets

Os lembretes, o resumo da manhã e o lembrete antes do término de uma avaliação gratuita são criados no seu dispositivo. Os widgets e as complicações do Apple Watch leem seus hábitos no seu dispositivo.

O Aplicativo pode mostrar uma Atividade ao Vivo da sua rotina da manhã na Tela Bloqueada e na Dynamic Island. Para que ela possa começar no horário da rotina e continuar avançando enquanto o Aplicativo está em repouso, o Aplicativo envia ao nosso pequeno servidor de retransmissão os tokens de notificação push que a Apple fornece a ele para as Atividades ao Vivo (um para iniciar a Atividade ao Vivo da rotina e outro para a Atividade ao Vivo em andamento) e a programação: os horários, identificadores aleatórios dos hábitos que fazem parte dela e seus números (quantos estão feitos, uma contagem e sua meta). Nenhum nome de hábito, texto que você digitou, nome, e-mail ou identificador de conta ou de dispositivo é enviado. Em cada momento da programação, o servidor pede ao serviço de notificações push da Apple que inicie ou atualize a Atividade ao Vivo, e apaga o que guarda assim que a notificação programada é enviada ou a Atividade ao Vivo termina. O servidor funciona no Cloudflare Workers; como qualquer serviço de internet, a Cloudflare vê o endereço IP da solicitação enquanto a entrega, e nós não o armazenamos. Se você desativar as Atividades ao Vivo para o Aplicativo em Ajustes do iOS, nada é enviado.

## 6. Game Center

Se você tiver iniciado sessão no Game Center, suas conquistas são informadas ao Game Center da Apple e tratadas nos termos da Política de Privacidade da Apple. Não recebemos sua identidade no Game Center.

## 7. Compras

As assinaturas são vendidas e processadas pela Apple por meio da App Store. Não recebemos seus dados de pagamento. A Apple informa ao Aplicativo se sua assinatura está ativa e qual plano você escolheu, com o preço; a seção 8 explica o que disso vai para nossas análises de uso.

## 8. Análises de uso e relatórios de falhas

Para saber quais recursos ajudam e onde o Aplicativo atrapalha, o Aplicativo envia sinais de uso anônimos ao TelemetryDeck, um serviço de análise da TelemetryDeck GmbH (Augsburgo, Alemanha) com servidores na UE. Um sinal indica uma ação no Aplicativo: por exemplo, que uma etapa da primeira abertura foi concluída, que a tela de assinatura foi exibida ou que uma assinatura foi iniciada, que o Aplicativo pediu uma avaliação ou que a sincronização com o iCloud falhou. Ele vem acompanhado de um carimbo de data e hora arredondado para a hora cheia e de dados técnicos gerais: as versões do Aplicativo e do iOS, o modelo do dispositivo, o idioma, a região e o fuso horário, além de ajustes de tela e de acessibilidade, como o modo escuro ou o tamanho do texto. Quando uma assinatura ou sua avaliação gratuita começa, o sinal também traz o plano, o preço convertido em dólares americanos, a moeda e o país da sua App Store, para que possamos ver quais planos são escolhidos.

Um sinal nunca contém os nomes dos seus hábitos ou qualquer outro texto que você digite, nem seu nome, endereço de e-mail, Conta Apple, amigos ou localização. Sua instalação é identificada apenas por um identificador aleatório ao qual o Aplicativo aplica um hash com salt antes do envio, de modo que os sinais não podem ser associados a você nem acompanhados entre aplicativos. O TelemetryDeck não armazena endereços IP e não usa cookies. Analisamos esses sinais apenas como estatísticas para melhorar o Aplicativo; não os vendemos, não os compartilhamos com anunciantes e não os usamos para rastrear você. O Aplicativo não contém código de publicidade ou rastreamento e não rastreia você em outros aplicativos ou sites.

Independentemente disso, se você optar por compartilhar análises com desenvolvedores de aplicativos em Ajustes do iOS > Privacidade e Segurança > Análise e Melhorias, a Apple poderá nos fornecer estatísticas de uso agregadas e anônimas e relatórios de falhas. Eles não identificam você.

## 9. O que o Aplicativo não usa

O Aplicativo não pede acesso à sua localização, aos seus contatos, às suas fotos, à câmera, ao microfone nem aos seus dados de saúde. O dia e a noite da vila seguem o relógio e o fuso horário do seu celular.

## 10. Crianças

O Aplicativo é adequado para todas as idades e não coleta intencionalmente informações pessoais de ninguém, incluindo crianças menores de 13 anos (ou da idade equivalente no seu país).

## 11. Retenção e exclusão de dados

Os dados permanecem pelo tempo que você os mantiver. Você pode apagar a qualquer momento um hábito e suas marcações no Aplicativo, e tudo apagando o Aplicativo e, no caso dos dados sincronizados, em Ajustes do iOS > [seu nome] > iCloud > Gerenciar Armazenamento da Conta > Hábitos. Como não mantemos nenhuma cópia, não há mais nada para apagarmos. O servidor de retransmissão mantém os tokens e a programação de uma Atividade ao Vivo somente até a notificação programada ser enviada ou essa Atividade ao Vivo terminar. Os sinais de uso são anônimos e não podem ser associados a você, portanto não existe nenhum registro pessoal deles para consultar ou apagar.

## 12. Seus direitos

Dependendo de onde você mora (por exemplo, nos termos do GDPR na UE, do UK GDPR, da CCPA/CPRA na Califórnia, da APPI no Japão, da PIPA na Coreia ou da LGPD no Brasil), você pode ter direito de acesso, correção, exclusão ou portabilidade dos seus dados pessoais, bem como direito de se opor ao tratamento deles ou de restringi-lo. Como não mantemos seus dados, você pode exercer esses direitos diretamente no seu dispositivo e no iCloud, conforme descrito acima. Você também pode entrar em contato conosco para qualquer solicitação ou dúvida e pode apresentar reclamação à autoridade de proteção de dados local.

Não vendemos nem compartilhamos informações pessoais, conforme definido na CCPA/CPRA.

## 13. Alterações

Se esta política for alterada, atualizaremos a data de vigência acima e, no caso de alterações relevantes, informaremos você no Aplicativo.

## 14. Contato

Stanislau Malchanau, Belarus
E-mail: 7tam.official@gmail.com
