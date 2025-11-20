# 🚨 Política de Privacidade - MakaNetu (Risk Place Angola)

<div align="center">
  <img src="logo.png" alt="MakaNetu Logo" width="150">
</div>

**Última Atualização:** 20 de Novembro de 2025  
**Versão:** 1.0.0

---

## 📌 Bem-vindo ao MakaNetu!

Esta Política de Privacidade descreve como coletamos, usamos, armazenamos e protegemos seus dados pessoais ao utilizar o aplicativo MakaNetu (Risk Place Angola). Ao usar nosso serviço, você concorda com as práticas descritas neste documento.

---

## 1. Identificação do Responsável

- **Nome do Serviço:** MakaNetu (Risk Place Angola)
- **Desenvolvedor:** Risk Place Angola
- **Website:** [https://github.com/risk-place-angola](https://github.com/risk-place-angola)
- **Email de Contato:** riskplaceangola@gmail.com
- **Tipo de Projeto:** Open Source (Código Aberto)

---

## 2. Aceitação da Política de Privacidade

Ao instalar, acessar ou utilizar o aplicativo MakaNetu, você concorda expressamente com os termos desta Política de Privacidade. Se você não concordar com qualquer parte desta política, não utilize o aplicativo.

---

## 3. Informações que Coletamos

O MakaNetu coleta diferentes tipos de informações, dependendo do modo de uso do aplicativo:

### 3.1. Dados de Localização Geográfica (GPS)

> **⚠️ INFORMAÇÃO CRÍTICA**  
> A coleta de dados de localização é **essencial** para o funcionamento do aplicativo. O MakaNetu é um sistema de segurança em tempo real que depende de sua localização precisa para:

- **Enviar alertas de emergência** com sua localização exata para entidades de resposta (ERCE/ERFCE)
- **Receber notificações** sobre incidentes próximos à sua localização
- **Visualizar no mapa** reports e alertas georeferenciados na sua área
- **Reportar incidentes** com precisão geográfica

#### Como Coletamos Localização:

- **Precisão:** Utilizamos GPS de alta precisão (bestForNavigation) com margem de 1 metro
- **Frequência:** Atualizações automáticas a cada 30 segundos ou quando você se move
- **Permissões:** Solicitamos permissão de localização "sempre ativa" ou "enquanto em uso"
- **Funcionamento em segundo plano:** A localização pode ser coletada mesmo quando o app não está aberto (para alertas de emergência)

#### Permissões Solicitadas:

- **iOS:** Location When In Use / Location Always
- **Android:** ACCESS_FINE_LOCATION / ACCESS_COARSE_LOCATION / ACCESS_BACKGROUND_LOCATION

### 3.2. Usuários Autenticados (com Conta)

Se você criar uma conta no MakaNetu, coletamos:

| Dado Pessoal | Finalidade | Obrigatório |
|--------------|------------|-------------|
| Nome completo | Identificação em reports e alertas | Sim |
| Endereço de e-mail | Autenticação, recuperação de senha, notificações | Sim |
| Senha (criptografada) | Segurança da conta | Sim |
| Número de telefone | Notificações SMS em emergências | Opcional |
| Foto de perfil | Identificação visual | Opcional |

### 3.3. Usuários Anônimos (sem Conta)

O MakaNetu permite uso anônimo, similar ao Waze. Se você usar sem criar conta, coletamos:

- **Device ID único (UUID v4):** Identificador anônimo gerado automaticamente
- **Localização GPS:** Apenas para receber alertas próximos
- **FCM Token:** Para notificações push
- **Dados de uso do app:** Eventos de abertura, crashes (via Firebase Analytics)

> **⚠️ IMPORTANTE:** Usuários anônimos **não podem** criar reports ou alertas, apenas receber notificações.

### 3.4. Dados de Incidentes

Quando você reporta um incidente (apenas usuários autenticados):

- **Localização do incidente:** Latitude, longitude, endereço
- **Tipo de risco:** Crime, infraestrutura, saúde, desastre natural, etc.
- **Descrição textual:** Detalhes do incidente
- **Fotos/Vídeos:** Mídia enviada (opcional)
- **Data e hora:** Timestamp da ocorrência

### 3.5. Dados Técnicos e de Dispositivo

- Modelo e fabricante do dispositivo
- Versão do sistema operacional (iOS/Android)
- Versão do aplicativo MakaNetu
- Endereço IP
- Logs de erro e crashes
- Idioma do dispositivo

### 3.6. Dados de Uso e Interação

- Páginas/telas visitadas no app
- Tempo de uso e frequência de acesso
- Interações com o mapa (zoom, pan, cliques)
- Reports confirmados ou comentados
- Configurações de notificações

---

## 4. Como Usamos Seus Dados

Utilizamos os dados coletados para as seguintes finalidades:

### 4.1. Funcionalidades Essenciais do Serviço

- **Geolocalização em tempo real:** Exibir sua posição no mapa e calcular proximidade a incidentes
- **Alertas de emergência:** Enviar sua localização exata para autoridades (ERCE/ERFCE) quando você acionar o botão de alerta
- **Notificações push:** Alertar sobre incidentes próximos à sua localização
- **Mapa colaborativo:** Exibir reports e alertas de outros usuários

### 4.2. Segurança e Prevenção

- Validar a autenticidade de reports (evitar spam e informações falsas)
- Detectar e prevenir uso malicioso ou fraudulento do aplicativo
- Proteger a integridade da comunidade e das entidades de resposta

### 4.3. Melhoria do Serviço

- Analisar padrões de uso para melhorar a experiência do usuário
- Identificar e corrigir bugs e erros técnicos
- Desenvolver novos recursos e funcionalidades

### 4.4. Comunicação com o Usuário

- Enviar notificações sobre atualizações do aplicativo
- Responder a solicitações de suporte técnico
- Informar sobre mudanças em termos e políticas

---

## 5. Compartilhamento de Dados

O MakaNetu **não vende** seus dados pessoais. Compartilhamos dados apenas nas seguintes situações:

### 5.1. Entidades de Resposta a Emergências (ERCE/ERFCE)

> **⚠️ IMPORTANTE:** Quando você aciona o botão de alerta de emergência, sua localização GPS em tempo real é automaticamente compartilhada com:
> 
> - **ERCE** (Entidades Responsáveis por Resolver Chamadas de Emergência): Polícia, Bombeiros, Hospitais, Proteção Civil
> - **ERFCE** (Entidades Responsáveis por Fazer Chamadas de Emergência): Centrais de atendimento de emergência
> 
> Este compartilhamento é **essencial para salvar vidas** em situações de emergência.

### 5.2. Comunidade de Usuários (Dados Públicos)

Reports de incidentes criados por você são **visíveis publicamente** no mapa para todos os usuários. Informações exibidas:

- Localização do incidente (não sua localização pessoal)
- Tipo de risco
- Descrição
- Fotos/vídeos (se enviados)
- Seu nome de usuário (se autenticado)

> **🔒 Privacidade:** Alguns alertas (ex: violência doméstica, sequestros) **não são exibidos publicamente** por motivos de segurança.

### 5.3. Provedores de Serviços Terceirizados

Utilizamos serviços de terceiros confiáveis para operar o aplicativo:

| Serviço | Provedor | Finalidade | Dados Compartilhados |
|---------|----------|------------|----------------------|
| Firebase Cloud Messaging (FCM) | Google LLC | Notificações push | Device ID, FCM Token, Localização |
| Firebase Analytics | Google LLC | Análise de uso | Eventos de uso, Device ID, Crashes |
| Firebase Authentication | Google LLC | Autenticação de usuários | Email, senha (hash), UID |
| Google Maps / Google Cloud | Google LLC | Mapas e geolocalização | Coordenadas GPS, Endereço |
| Twilio | Twilio Inc. | Notificações SMS | Número de telefone (opcional) |

**Políticas de Privacidade de Terceiros:**

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Twilio Privacy Policy](https://www.twilio.com/legal/privacy)

### 5.4. Requisições Legais e Proteção de Direitos

Podemos divulgar seus dados se legalmente obrigados:

- Em resposta a ordens judiciais, mandados ou requisições governamentais
- Para cumprir leis e regulamentações aplicáveis
- Para proteger direitos, propriedade ou segurança do MakaNetu, usuários ou terceiros
- Para prevenir fraudes, crimes ou violações dos Termos de Uso

---

## 6. Armazenamento e Segurança dos Dados

### 6.1. Onde Armazenamos Seus Dados

- **Banco de Dados:** PostgreSQL com criptografia em trânsito (TLS/SSL)
- **Cache:** Redis para dados temporários de localização
- **Armazenamento de mídia:** Firebase Storage (Google Cloud)

### 6.2. Medidas de Segurança

Implementamos as seguintes proteções para garantir a segurança dos seus dados:

- **Criptografia TLS/SSL:** Todas as comunicações entre o app e servidor são criptografadas
- **Autenticação JWT:** Tokens de segurança para sessões autenticadas
- **Hashing de senhas:** Senhas armazenadas com bcrypt (não guardamos senhas em texto puro)
- **WebSocket seguro (WSS):** Comunicação real-time criptografada
- **Validação de entrada:** Todos os dados são validados para prevenir injeções e ataques
- **Logs de segurança:** Monitoramento de atividades suspeitas
- **Rate limiting:** Proteção contra ataques DDoS e força bruta

> **⚠️ AVISO:** Embora utilizemos as melhores práticas de segurança, nenhum sistema é 100% inviolável. Você é responsável por manter a senha da sua conta segura.

### 6.3. Retenção de Dados

Mantemos seus dados pelo tempo necessário para fornecer o serviço:

- **Dados de conta:** Enquanto a conta estiver ativa
- **Localização GPS:** 24 horas (depois são anonimizados para estatísticas)
- **Reports de incidentes:** Permanentemente (histórico público de segurança)
- **Logs de erros:** 90 dias
- **Dados de usuários anônimos:** 30 dias sem atividade

---

## 7. Seus Direitos e Controles

Você tem os seguintes direitos sobre seus dados pessoais:

### 7.1. Acesso e Portabilidade

- **Acessar:** Visualizar todos os dados que coletamos sobre você
- **Exportar:** Baixar uma cópia de seus dados em formato JSON

### 7.2. Retificação

- Atualizar informações de perfil (nome, email, foto) diretamente no app
- Solicitar correção de dados incorretos

### 7.3. Exclusão ("Direito ao Esquecimento")

- **Excluir conta:** Você pode apagar sua conta e todos os dados associados diretamente no aplicativo
- **Processo:** Configurações → Conta → Excluir Conta
- **Consequências:** Seus reports públicos permanecerão visíveis, mas de forma anonimizada

### 7.4. Oposição e Limitação de Processamento

- **Desativar notificações:** Configurações do app ou configurações do sistema operacional
- **Revogar permissão de localização:** Configurações do dispositivo (o app deixará de funcionar corretamente)

### 7.5. Como Exercer Seus Direitos

Para exercer qualquer um desses direitos, entre em contato conosco:

- **📧 Email:** riskplaceangola@gmail.com
- **⏱️ Tempo de resposta:** Até 30 dias
- **📄 Documentação:** Pode ser necessário verificar sua identidade

---

## 8. Dados de Menores de Idade

> **⚠️ IMPORTANTE:** O MakaNetu **não é destinado a menores de 13 anos**.

- Não coletamos intencionalmente dados de crianças menores de 13 anos
- Se descobrirmos que uma criança forneceu dados pessoais, excluiremos imediatamente
- Pais/responsáveis que acreditam que seus filhos forneceram informações devem nos contatar imediatamente

---

## 9. Cookies e Tecnologias de Rastreamento

O aplicativo mobile **não utiliza cookies**, mas usa tecnologias similares:

- **SharedPreferences/UserDefaults:** Armazenamento local de configurações e Device ID
- **Firebase Analytics SDK:** Coleta eventos de uso anônimos
- **FCM Token:** Identificador único para notificações push

Você pode desativar rastreamento de uso em: **Configurações → Privacidade → Analytics**

---

## 10. Transferências Internacionais de Dados

Seus dados podem ser transferidos e armazenados em servidores localizados fora de Angola:

- **Estados Unidos:** Google Firebase
- **União Europeia:** Possíveis servidores de distribuição

Garantimos que essas transferências seguem padrões internacionais de proteção de dados (GDPR, CCPA).

---

## 11. Alterações nesta Política de Privacidade

- Podemos atualizar esta Política periodicamente
- Você será notificado sobre mudanças significativas através de:
  - Notificação push no aplicativo
  - Email (se cadastrado)
  - Banner na tela inicial
- Continuação do uso após mudanças significa aceitação dos novos termos
- Versão atual sempre disponível em: [https://risk-place-angola.github.io/privacy-policy](https://risk-place-angola.github.io/privacy-policy)

---

## 12. Legislação Aplicável

Esta Política de Privacidade é regida pelas seguintes leis:

- **Lei de Proteção de Dados de Angola** (quando aplicável)
- **GDPR** (General Data Protection Regulation - União Europeia)
- **Google Play e App Store** políticas de privacidade
- **Lei Geral de Proteção de Dados (LGPD)** do Brasil (para usuários brasileiros)

---

## 13. Resolução de Disputas

Em caso de conflito relacionado a esta Política:

- Tentaremos resolver amigavelmente através do email de suporte
- Foro competente: Tribunais de Angola (Luanda)

---

## 14. Projeto Open Source

> **🔓 Código Aberto:** O MakaNetu é um projeto open source!
> 
> Você pode auditar nosso código-fonte e práticas de privacidade em:
> 
> - **Backend:** [github.com/risk-place-angola/backend-risk-place](https://github.com/risk-place-angola/backend-risk-place)
> - **Mobile:** [github.com/risk-place-angola/mobile-risk-place](https://github.com/risk-place-angola/mobile-risk-place)
> - **Frontend:** [github.com/risk-place-angola/frontend-risk-place](https://github.com/risk-place-angola/frontend-risk-place)

---

## 15. Contato e Suporte

### 📞 Como Entrar em Contato

- **Email Principal:** riskplaceangola@gmail.com
- **GitHub Issues:** [github.com/risk-place-angola/mobile-risk-place/issues](https://github.com/risk-place-angola/mobile-risk-place/issues)
- **Discord Comunidade:** [discord.gg/s2Nk4xYV](https://discord.gg/s2Nk4xYV)
- **GitHub Discussions:** [github.com/risk-place-angola/backend-risk-place/discussions](https://github.com/risk-place-angola/backend-risk-place/discussions)

### 🕐 Horário de Atendimento

- Segunda a Sexta-feira: 9h - 17h (WAT - West Africa Time)
- Tempo de resposta: Até 72 horas úteis

---

## 16. Glossário de Termos

- **ERCE:** Entidade Responsável por Resolver Chamadas de Emergência (Polícia, Bombeiros, Hospitais)
- **ERFCE:** Entidade Responsável por Fazer Chamadas de Emergência (Centrais de atendimento)
- **Device ID:** Identificador único anônimo gerado para usuários sem conta
- **FCM:** Firebase Cloud Messaging - serviço de notificações push do Google
- **GPS:** Global Positioning System - sistema de localização por satélite
- **Report:** Relatório de local de risco criado por usuário
- **Alert:** Alerta de emergência acionado através do botão de emergência
- **JWT:** JSON Web Token - método de autenticação segura
- **WebSocket:** Protocolo de comunicação em tempo real

---

## 17. Conformidade com Google Play e App Store

Esta Política de Privacidade está em conformidade com:

- **Google Play:** Developer Program Policies - User Data
- **App Store:** App Store Review Guidelines - Privacy
- **Firebase:** Google's EU User Consent Policy

---

## 18. Declaração de Transparência

O MakaNetu se compromete com a transparência total:

- ✅ Nunca vendemos dados pessoais
- ✅ Não exibimos anúncios (aplicativo 100% gratuito)
- ✅ Código-fonte aberto para auditoria pública
- ✅ Coleta mínima de dados necessária para funcionamento
- ✅ Sem rastreamento cross-site ou fingerprinting
- ✅ Sem uso de dados para machine learning sem consentimento

---

## 19. Segurança da Informação - Responsabilidades do Usuário

Você também tem responsabilidades para manter seus dados seguros:

- Criar senha forte e única
- Não compartilhar sua senha com terceiros
- Fazer logout em dispositivos compartilhados
- Manter o aplicativo atualizado
- Reportar atividades suspeitas imediatamente

---

## 20. Consentimento Explícito

> **✅ Ao usar o MakaNetu, você consente expressamente com:**
> 
> - Coleta e processamento de dados de localização GPS em tempo real
> - Compartilhamento de localização com entidades de emergência (ERCE/ERFCE) ao acionar alertas
> - Armazenamento de dados em servidores localizados fora de Angola
> - Uso de serviços de terceiros (Firebase, Google Maps, Twilio)
> - Exibição pública de reports de incidentes que você criar

---

## 21. Direito de Reclamação

Se você acredita que seus direitos de privacidade foram violados, você tem o direito de:

- Registrar uma reclamação formal conosco: riskplaceangola@gmail.com
- Contatar autoridades de proteção de dados de Angola
- Para usuários europeus: Contatar sua autoridade de proteção de dados local (GDPR)

---

## 📄 Informações do Documento

- **Versão:** 1.0.0
- **Data de Criação:** 20 de Novembro de 2025
- **Última Atualização:** 20 de Novembro de 2025
- **URL Permanente:** [https://risk-place-angola.github.io/privacy-policy](https://risk-place-angola.github.io/privacy-policy)

---

<div align="center">

**MakaNetu (Risk Place Angola)**

*Maka = Problema | Netu = Nosso | MakaNetu = Resolver problemas juntos*

🗺️🚨 **Mapping risks, saving lives**

Made with ❤️ by the Risk Place Angola team

</div>
