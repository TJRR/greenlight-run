# Conheça o Scriba
O Scriba é um sistema de audiências via web de código aberto, o que significa que o código-fonte possui uma licença que permite a qualquer instituição do Judiciário configurar seu próprio serviço de comunicação inteligente com o Scriba.

O Scriba foi concebido para Tribunais, por isso apresenta todos recursos esperados de um sistema de Audiências Judiciais. Os recursos abrangentes permitem aos magistrados, servidores, promotores, defensores, advogados e as partes participarem das audiências de maneira célere e segura.

O Scriba pode ser integrado ao sistema de controle de processos para realizar a gravação e a transcrição das audiências diretamente da tela de gestão da pauta diária da Unidade Judicial.

O Scriba permite a participação remota a partir de qualquer dispositivo com acesso a internet, inclusive de réus em regime de restrição de liberdade, sem a necessidade de deslocamento com escolta da unidade prisional até o Fórum.

## Licença
O Scriba é uma ramificação (fork) do Software Mconf.org, que por sua vez é um fork do software BigBlueButton.

O Mconf é um sistema de conferência na web de código aberto. <a href="http://mconf.org/#open-source">CONSULTAR LICENÇA</a>.

O BigBlueButton é um sistema de conferência web voltado para aprendizagem on-line, também de código aberto. <a href="https://bigbluebutton.org/open-source-license/">CONSULTAR LICENÇA</a>.

O Scriba está sob a licença <bold>LGPL versão 3</bold>, <a href="https://bigbluebutton.org/open-source-license/">CONSULTAR LICENÇA</a>.

Como seus antencessores, todos os componentes inclusos no Scriba são originários do projeto BigBlueButton e Mconf, e estão disponíveis sob a licença GNU Lesser General Public License, assim como todas as personalizações e melhorias desenvolvidas pelo TJRR respeitam integralmente todas as diretrizes desta licença.

# Greenlight

![Travis CI](https://travis-ci.org/bigbluebutton/greenlight.svg?branch=master)
![Coverage
!Status](https://coveralls.io/repos/github/bigbluebutton/greenlight/badge.svg?branch=master)
![Docker Pulls](https://img.shields.io/docker/pulls/bigbluebutton/greenlight.svg)

> Greenlight is currently on version 2.0. If you are still running Greenlight 1.0 we suggest [upgrading to 2.0](http://docs.bigbluebutton.org/install/greenlight-v2.html#upgrading-from-greenlight-10).

Greenlight is a simple front-end interface for your BigBlueButton server. At it's heart, Greenlight provides a minimalistic web-based application that allows users to:

  * Signup/Login with Twitter, Google, or through the application itself.
  * Manage your account settings and user preferences.
  * Create and manage your own personal rooms ([BigBlueButton](https://github.com/bigbluebutton/bigbluebutton) sessions).
  * Invite others to your room using a simple URL.
  * View recordings and share them with others.

Interested? Try Greenlight out on our [demo server](https://demo.bigbluebutton.org/gl)!

Greenlight is also completely configurable. This means you can turn on/off features to make Greenlight fit your specific use case. For more information on Greenlight and its features, see our [documentation](http://docs.bigbluebutton.org/install/greenlight-v2.html).

For a overview of how Greenlight works, checkout our Introduction to Greenlight Video:

[![GreenLight Overview](https://img.youtube.com/vi/Hso8yLzkqj8/0.jpg)](https://youtu.be/Hso8yLzkqj8)

## Installation on a BigBlueButton Server

Greenlight is designed to work on a [BigBlueButton 2.0](https://github.com/bigbluebutton/bigbluebutton) (or later) server.

For information on installing Greenlight, checkout our [Installing Greenlight on a BigBlueButton Server](http://docs.bigbluebutton.org/install/greenlight.html#installing-on-a-bigbluebutton-server) documentation.

## Source Code & Contributing

Greenlight is built using Ruby on Rails. Many developers already know Rails well, and we wanted to create both a full front-end to BigBlueButton but also a reference implementation of how to fully leverage the [BigBlueButton API](http://docs.bigbluebutton.org/dev/api.html).

We invite you to build upon GreenLight and help make it better. See [Contributing to BigBlueButton](http://docs.bigbluebutton.org/support/faq.html#contributing-to-bigbluebutton).

We invite your feedback, questions, and suggests about GreenLight too. Please post them to the [developer mailing list](https://groups.google.com/forum/#!forum/bigbluebutton-dev).
