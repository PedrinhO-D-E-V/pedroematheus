# Montagem e Desmontagem de Computadores

Guia prático desenvolvido a partir do roteiro utilizado na atividade de manutenção,
            organizado para orientar desde a preparação da bancada até a primeira inicialização do computador.

## Antes de começar
A montagem e a desmontagem de um computador exigem organização, cuidado e atenção aos componentes.
            Prepare a bancada e mantenha o equipamento desligado e desconectado da energia elétrica.

### 🖥️ O que será trabalhado?
- Gabinete e organização interna.
- Placa-mãe.
- Processador e cooler.
- Memória RAM.
- Fonte de alimentação.
- SSDs e HDDs.
- Cabos de alimentação e dados.
- Placas de expansão, quando existentes.

### ⚠️ Segurança
Nunca force um componente ou conector. Se uma peça não encaixar, confira a posição, o tipo de conexão e a compatibilidade antes de continuar.

Trabalhe com cuidado para evitar eletricidade estática e danos aos contatos dos componentes.

## Ferramentas necessárias
Ferramentas básicas utilizadas para montagem, desmontagem, limpeza e manutenção.

### 🪛 Chaves
- Chave de fenda 3/16"
- Chave de fenda 1/8"
- Chave Phillips #1
- Chave Phillips #0
- Chave Torx T15
- Chave de fenda soquete 1/4"
- Chave de fenda soquete 3/16"
- Chave-teste

### 🔧 Diagnóstico e apoio
- Multímetro
- Extrator de IC
- Alicate de bico longo de 5"
- Pinça
- Pincel para limpeza

### 📦 Organização
- Tubo/recipiente para acessórios e componentes.
- Estojo com zíper para ferramentas e peças pequenas.

## Passo a passo da desmontagem
A sequência abaixo preserva a numeração e as etapas do roteiro-base da prática.

### 1. Desligar e desconectar

Desligue o computador pelo sistema operacional e retire o cabo de alimentação da fonte. Depois, desconecte todos os periféricos e cabos externos.

- Teclado
- Mouse
- Monitor
- Impressora
- Caixas de som
- Cabo de rede
- Dispositivos USB

### 2. Abrir o gabinete

Remova os parafusos da tampa lateral e retire-a com cuidado.

![Abertura do gabinete](https://i.imgur.com/I5TiUie.png)

*Acesso ao interior do gabinete.*

### 3. Desconectar a fonte de alimentação

Desconecte os cabos da fonte dos componentes.

- **24 pinos ATX** → alimentação principal da placa-mãe.
- **4/8 pinos EPS/CPU** → alimentação do processador.
- **PCIe 6/8 pinos** → alimentação de placas de vídeo.
- **SATA Power** → SSDs, HDDs e dispositivos SATA.
- **Molex** → presente em computadores ou acessórios mais antigos.

> 💡 Não puxe os cabos pelos fios. Segure o conector ao desconectá-lo.

![Cabos da fonte](https://i.imgur.com/4kwyrW1.png)

*Conectores da fonte.*

![Conexões de alimentação](https://i.imgur.com/gROuoP6.png)

*Desconexão dos cabos de alimentação.*

### 4. Remover a fonte

Após desconectar os cabos, remova os parafusos que prendem a fonte ao gabinete e retire-a cuidadosamente.

![Remoção da fonte](https://i.imgur.com/e9wmIlJ.png)

*Retirada da fonte de alimentação.*

### 5. Remover placas de expansão

Quando existirem, remova placas de vídeo, som, rede, captura e outras PCI/PCIe.

Antes, remova os parafusos de fixação e desconecte os cabos de alimentação, quando houver.

![Placa de expansão](https://i.imgur.com/Y9X6T5M.png)

*Placa de expansão.*

![Remoção de placa](https://i.imgur.com/zzPvobR.png)

*Retirada da placa do gabinete.*

### 6. Desconectar os cabos de dados

Desconecte os cabos responsáveis pela comunicação com os dispositivos de armazenamento.

- **SATA Data** → SSDs SATA e HDDs.
- Outros cabos de dados, dependendo do equipamento.

![Cabo SATA](https://i.imgur.com/uC87u1x.png)

*Conexão de dados SATA.*

### 7. Remover os dispositivos de armazenamento

Remova os dispositivos instalados no gabinete:

- HDD
- SSD SATA
- Unidades ópticas, caso existam

> ⚠️ SSDs M.2 são instalados diretamente na placa-mãe e possuem procedimento diferente dos dispositivos SATA.

![Dispositivo de armazenamento](https://i.imgur.com/VoXWZXF.png)

*Armazenamento do computador.*

### 8. Remover a memória RAM

Abra as travas laterais do slot e retire o módulo segurando-o pelas bordas. Evite tocar diretamente nos contatos dourados.

![Memória RAM](https://i.imgur.com/gZbBdsu.png)

*Memória RAM no slot.*

![Remoção da RAM](https://i.imgur.com/oWmlKBG.png)

*Retirada da memória RAM.*

### 10. Remover o cooler do processador

Desconecte a ventoinha do conector **CPU_FAN** e remova o sistema de fixação do cooler de acordo com o modelo.

> ⚠️ Se o cooler estiver preso pela pasta térmica, não force. Faça movimentos leves para soltá-lo.

![Cooler do processador](https://i.imgur.com/LeLEUZ1.png)

*Cooler antes da retirada.*

![Remoção do cooler](https://i.imgur.com/IkCMYKV.png)

*Remoção do sistema de refrigeração.*

### 11. Remover o processador

1. Abra o mecanismo de retenção do soquete.
2. Retire cuidadosamente o processador.
3. Segure-o pelas bordas.
4. Coloque-o em uma superfície ou embalagem adequada.

> ⚠️ Evite tocar desnecessariamente nos contatos do processador ou do soquete.

![Processador](https://i.imgur.com/UhSESHd.png)

*Processador.*

![Soquete do processador](https://i.imgur.com/8eFwjoV.png)

*Soquete da placa-mãe.*

### 12. Remover a placa-mãe

Confirme que todos os cabos e componentes estão desconectados. Depois:

1. Remova os parafusos que prendem a placa-mãe ao gabinete.
2. Segure a placa pelas bordas.
3. Retire-a cuidadosamente do chassi.

![Placa-mãe](https://i.imgur.com/FMt6K49.png)

*Placa-mãe fora do gabinete.*

## Limpeza dos componentes
Com o computador desmontado, aproveite para remover poeira e sujeira acumulada.

### 🧹 Materiais
- Pincel adequado.
- Ar comprimido, quando disponível.
- Produtos apropriados para limpeza eletrônica.

### ⚠️ Cuidados
- Não utilize água diretamente nos componentes.
- Evite força excessiva.
- Não utilize objetos metálicos para remover poeira.
- Tenha cuidado com ventoinhas e conectores.
- Evite gerar eletricidade estática.

## Passo a passo da montagem
Agora o procedimento é realizado novamente de forma organizada, respeitando a ordem do roteiro-base.

### 1. Preparar o gabinete

Verifique se o gabinete possui:

- Parafusos para fixação da placa-mãe.
- Parafusos da fonte.
- Parafusos das unidades de armazenamento.
- Parafusos das placas de expansão.
- Cabos do painel frontal.
- Cabos USB.
- Cabo de áudio frontal.
- Espaço adequado para os componentes.

Confira também se os **espaçadores (standoffs)** da placa-mãe estão posicionados corretamente.

> ⚠️ Nunca instale a placa-mãe diretamente sobre o chassi metálico sem os espaçadores apropriados.

![Espaçadores do gabinete](https://i.imgur.com/pZ68LO3.png)

*Espaçadores para fixação da placa-mãe.*

### 2. Instalação da placa-mãe

Posicione a placa-mãe cuidadosamente dentro do gabinete, alinhando-a aos espaçadores e à região traseira do gabinete.

1. Alinhe os furos da placa-mãe.
2. Coloque os parafusos.
3. Aperte-os sem aplicar força excessiva.

![Instalação da placa-mãe](https://i.imgur.com/FMt6K49.png)

*Posicionamento da placa-mãe.*

![Fixação da placa-mãe](https://i.imgur.com/dvOCEwU.png)

*Fixação da placa-mãe.*

### 3. Instalação do processador

1. Localize o soquete da CPU.
2. Abra o mecanismo de retenção.
3. Identifique a marcação de orientação do processador.
4. Posicione o processador corretamente.
5. Feche o mecanismo de retenção.

> ⚠️ O processador deve encaixar naturalmente. Nunca force a CPU no soquete.

![Instalação do processador](https://i.imgur.com/twxsqdv.png)

*Posicionamento da CPU.*

### 4. Pasta térmica e cooler

A pasta térmica auxilia na transferência de calor entre o processador e o dissipador.

1. Verifique se as superfícies estão limpas.
2. Aplique uma pequena quantidade de pasta térmica, conforme a recomendação do fabricante.
3. Instale o dissipador/cooler.
4. Fixe corretamente o cooler.
5. Conecte a ventoinha ao conector **CPU_FAN**.

![Pasta térmica](https://i.imgur.com/AwtcqGB.png)

*Aplicação da pasta térmica.*

![Cooler](https://i.imgur.com/fpuQou7.png)

*Instalação do cooler.*

![Conector CPU FAN](https://i.imgur.com/SA29Bgh.png)

*Conexão do CPU_FAN.*

### 5. Instalação da memória RAM

1. Verifique a orientação do módulo.
2. Alinhe o encaixe da RAM ao slot.
3. Pressione o módulo uniformemente até que esteja travado.

#### 🔵 Dual Channel

Quando houver dois módulos, utilize os slots recomendados pelo manual da placa-mãe. A posição varia de acordo com o modelo; em muitas placas são usados A2 e B2.

![Memória RAM](https://i.imgur.com/eHBzcqP.png)

*Instalação da memória.*

![Slots da memória RAM](https://i.imgur.com/qZfPIex.png)

*Slots de memória.*

### 6. Instalação da placa de vídeo

Caso o computador possua GPU dedicada, instale-a no slot PCI Express, fixe-a ao gabinete e conecte os cabos de alimentação PCIe quando necessários.

> 🎮 Na máquina utilizada pela escola, não havia placa de vídeo dedicada .

### 7. Instalação dos dispositivos de armazenamento

#### SSD/HDD SATA

**SSD/HDD → cabo SATA → placa-mãe**  
 **SSD/HDD → cabo SATA Power → fonte**

#### SSD M.2

1. Localize o slot M.2.
2. Insira o SSD no ângulo indicado.
3. Abaixe cuidadosamente o dispositivo.
4. Fixe-o com o parafuso apropriado.

![SSD](https://i.imgur.com/E3XkUAI.png)

*Dispositivo de armazenamento.*

![Instalação de armazenamento](https://i.imgur.com/pZZYRnx.png)

*Instalação do dispositivo.*

![SSD M.2](https://i.imgur.com/axvAQuw.png)

*Dispositivo de disco físico*

### 8. Instalação da fonte de alimentação

Posicione a fonte no local apropriado do gabinete.

1. Alinhe os furos.
2. Coloque os parafusos.
3. Aperte-os adequadamente.

![Instalação da fonte](https://i.imgur.com/036e55i.png)

*Fixação da fonte.*

### 9. Conectar os cabos da fonte

> ⚠️ Não confunda os cabos de alimentação de CPU e PCIe. Eles possuem funções diferentes.

![Conectores da fonte](https://i.imgur.com/LHxStux.png)
*Cabos de alimentação.*

![Conexão da fonte](https://i.imgur.com/TAZd3yZ.png)

*Conexões da fonte.*

### 10. Conectar as ventoinhas

- **CPU_FAN** → cooler do processador.
- **SYS_FAN/CHA_FAN** → ventoinhas do gabinete.

Verifique se as ventoinhas estão instaladas na direção correta para criar um fluxo de ar adequado.

![Ventoinha](https://i.imgur.com/VJyJnUI.png)

*Ventoinha do gabinete.*

![Conector de ventoinha](https://i.imgur.com/9vfHscN.png)

*Conexão das ventoinhas.*

![Fluxo de ar](https://i.imgur.com/lLO40zI.png)

*Organização do fluxo de ar.*

### 11. Conferência antes de ligar

Antes de conectar o computador à tomada, faça uma inspeção geral.

- Processador instalado corretamente
- Cooler instalado
- Cabo CPU_FAN conectado
- Memória RAM corretamente encaixada
- Placa de vídeo instalada, se houver
- SSD/HDD instalado
- Cabos SATA conectados
- ATX 24 pinos conectado
- CPU/EPS conectado
- Alimentação da GPU conectada, se necessário
- Cabos do painel frontal conectados
- USB frontal conectado
- Áudio frontal conectado
- Ventoinhas conectadas
- Nenhum cabo encostando nas ventoinhas
- Nenhum parafuso solto dentro do gabinete
- Componentes devidamente fixados

### 12. Primeira inicialização

1. Conecte o cabo de alimentação.
2. Conecte monitor, teclado e mouse.
3. Ligue o computador.
4. Observe se as ventoinhas começam a girar.
5. Verifique se aparece imagem no monitor.

## Fluxo completo da prática

### 🔴 Desmontagem
Desligar → abrir gabinete → desconectar → remover componentes.

### 🧹 Limpeza
Remover poeira com os materiais apropriados e cuidado.

### 🟢 Montagem
Reinstalar componentes → conectar cabos → conferir → ligar.
