<img src="https://cdn.rawgit.com/pagarme/brand/9ec30d3d4a6dd8b799bca1c25f60fb123ad66d5b/logo-circle.svg" width="127px" height="127px" align="left"/>

# mpos-net-sdk

<br/>

# Components

## PagarMe.Mpos

Pagarme's .NET SDK for mPOS.

## PagarMe.Mpos.Bridge

Actual bridge implementation.

## PagarMe.Mpos.Bridge.Server

Standalone bridge server as a console application.

## PagarMe.Mpos.Bridge.Service

Bridge server as a Windows service.

## Setup

Setup package. Installs and registers the Windows service.

# Usage

## Library

The library exposes all needed interfaces directly.

## Bridge

Currently the bridge exposes mPOS devices on an websocket endpoint. You can check its documentation [here](docs/websocket.md).

In the future, SOAP/WCF and REST implementations are expected.

# Documentation

You can find more details about this project [here](docs/).

# License

See [here](LICENSE.md).

