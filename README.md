# kurea-contrib-wolfram

A WolframAlpha query module for Kurea.

## Installation

### npm

To install from npm, run this command in the directory where you installed Kurea:

`npm install kurea-contrib-wolfram`

### Kurea Package Manager

To install from Kurea at runtime, give Kurea this command:

`!package install kellyirc/kurea-contrib-wolfram`

### API Key

To use this module, Kurea must be given a WolframAlpha API key. Add it to Kurea's `config.json` or add it at runtime with `!set-api-key wolfram [api key]`.

## Usage

`!wolfram query`

 - `query`: the WolframAlpha query you want an answer for
 