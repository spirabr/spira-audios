# SPIRA Audios

Este é um repositório para armazenar áudios exemplo para a coleta de áudio do projeto [SPIRA](https://spira.ime.usp.br/coleta/). Os áudios aqui contidos são amostras dos áudios coletados no aplicativo em desenvolvimento.

## Nomenclatura
Os nomes dos arquivos seguem o seguinte modelo:

\[tipo\]\_\[flags\]\_\[modelo\]\_\[autor\]\.wav

 - **tipo:** Tipo de gravação realizado
 - **flags:** Dígitos de 0 ou 1 indicando as configurações utilizadas na gravação
 - **modelo:** Modelo do aparelho utilizado durante a gravação, sendo os 3 primeiros caracteres referentes ao fabricante (Ex.: Apple -> Apl ; Motorola -> Mot), e o restante o modelo.
 - **autor:** Sobrenome do autor, seguido da inicial do primeiro nome

### Tipo
Natureza da gravação, pode ser um dos itens abaixo:
 - `vogal`: Vogal Sustentada
 - `parlenda`: Parlenda
 - `frase`: Frase longa, lida na hora pelo paciente

### Flags
Flags que indicam os processamentos utilizados no microfone no momento da gravação, sendo 0 para desativado e 1 para ativado. A tabela abaixo indica a posição do dígito de cada flag:
| Dígito | Flag |
|-- |--|
| 1 | Supressão de ruído           |
| 2 | Cancelamento de eco          |
| 3 | Controle de ganho automático |


### Exemplo
O nome de arquivo `SsgS20_NakazawaR_010.wav` indica:

 * Modelo: Samsung S20
 * Autor: Renan Nakazawa
 * Flags
	 * Supressão de ruído **desativado**
	 * Cancelamento de eco **ativado**
	 * Controle de ganho automático **desativado**
