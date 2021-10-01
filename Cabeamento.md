# Influência do cabeamento na performance de redes locais de computadores

Bem-vindos

Neste documento você vai encontrar o uma breve explicação de cabeamento.

# Importância do assunto
- Cabeamento é colocado, muitas vezes, em um plano secundário no projeto de redes;
- Cabeamento estruturado ainda é pouco difundido nas escolas de formação;
- Cabeamento pode influir negativamente sobre a performance das redes.
# Testes passivos em Cabeamento

## Diferenciar cabos metálicos de óticos;
- Cabos metálicos -> sinais elétricos
  - Cabos coaxiais e par trançado;
  - ondutores elétricos;
- Cabos óticos -> sinais de luz
  - Fibra ótica;
  - Isolante elétrico;
## Equipamentos usados
- Testadores de cabo
- Certificadores

![image](https://user-images.githubusercontent.com/66855310/135639977-ec70be8f-7273-405b-9c5d-0fd245dfa37c.png)

## Canal e Link
![image](https://user-images.githubusercontent.com/66855310/135640168-06d470ea-c671-45d7-86af-e10fa0649790.png)

## Link permanente
![image](https://user-images.githubusercontent.com/66855310/135640361-33f23bd0-9e62-4906-920e-c19b957dae22.png)

# Testes passivos em Cabeamento Metálico
- Comprimento
  - Distância máxima entre pontos ativos (placas de rede, HUBs, Switchs, repetidores) da rede; 
  - 100m (3m + 90m + 7m);
- Atenuação (Perda de inserção)
  - Perda de potência do sinal elétrico;
- Crosstalk (Linha cruzada)
  - Um condutor induz sinais elétricos nos condutores vizinhos através do campo elétrico criado ao seu redor;
  - Trançamento dos fios nos cabos par trançado visa diminuir este problema através da técnica de cancelamento (um fio, do par, conduz e o outro não);
- Tipos de medida de Crosstalk
  - NEXT (Near end Crosstalk);
  - PS-NEXT (Power Sum NEXT);
  - FEXT (Far End Crosstalk);
  - ELFEXT (Equal Level FEXT);
  - PS-ELFEXT;
- Wiremap (mapa de fiação)
  - Testa a continuidade fio a fio;
  - Identifica par cruzado, par aberto, par reverso;
- Impedância
  - Conjunto das características elétricas resistivas de um condutor;
  - Resistência + Reatância capacitiva + Reatância indutiva;
  - Em torno de 100 em cabos par trançado;
- Perda de Retorno (RL)
  - Diferenças de impedância no percurso do sinal entre a placa de rede e o equipamento ativo (hub ou switch) provocam reflexões;
- ACR (Relação Atenuação e Crosstalk)
  - Medida de qualidade do cabeamento instalado;
- Propagation Delay e Delay Skew
  - Atraso de propagação é o tempo que o sinal leva para percorrer o cabeamento;
  - Desvio de propagação é a diferença de propagação entre os pares de um cabo;
- EMI (Interferência eletromagnética)
  - Motores elétricos;
  - Reatores;
  - Fontes chaveadas;
  - Sistemas de alarme;
- RFI (Interferência de rádio-freqüência)
  - Antenas;
  - Equipamentos de comunicação;
# Testes passivos em Cabeamento Metálico
- Comprimento
![image](https://user-images.githubusercontent.com/66855310/135654752-65bcae8c-d0c3-4383-9134-3007b0e41f57.png)
![image](https://user-images.githubusercontent.com/66855310/135654810-cec719a8-2df8-40a7-a276-c0578c56ee64.png)
- Atenuação Ótica
  - Perda de potência ótica do sinal;
- Dispersões
  - DISPERSÃO MODAL<br/>
    Este tipo de dispersão só existe em fibras do tipo multimodo (degrau e gradual) e é provocada basicamente pelos vários caminhos possíveis de propagação (modos) que a luz pode ter no núcleo. 
  - DISPERSÃO CROMÁTICA<br/>
    Esse tipo de dispersão depende do comprimento de onda.
- Absorção
	- é o mecanismo de atenuação que exprime a dissipação de parte da energia transmitida numa fibra óptica em forma de calor. 
- Deformações Mecânicas
  - Macrocurvaturas
  - Microcurvaturas
- As deformações, as quais ocorrem ao longo da fibra devido à aplicação de esforços sobre a mesma durante a confecção e instalação do cabo.
- Equipamentos Usados
  - Fonte Ótica + Medidor de Potência Ótica
  - OTDR
  
![image](https://user-images.githubusercontent.com/66855310/135655321-ea6a4f4c-b97a-4148-a4d1-3fb94c9de7bb.png)

# Testes ativos em Cabeamento
- Colisões
  - Problemas de comprimento e atenuação aumentam o número de colisões em uma rede CSMA/CD;
- BER (Bit Error Rate)
  - BER = Número de erros de bit / Total de bits
  - Baixa BER indica que o cabeamento não está distorcendo a forma de onda transmitida;
  - Alta BER tem que ser combinada com testes passivos para evitar uma conclusão precipitada;
  - Equipamentos de comunicação que apresentem mau funcionamento podem afetar negativamente a BER;
# Medidas Corretivas 
- Utilização de cabos de categoria superior
  - Categoria 5E (Classe D);
  - Categoria 6 (Classe E);
  - Categoria 7 (Classe F);
- Utilização de cabos de categoria superior <br/>

  - Tipo do Cabo			      RL(db)  <br/>	
  - Categoria 5	  Canal	       8	  <br/>
				      Link		    10,1	<br/>
  - Categoria 5e	Canal	      10	  <br/>
				      Link		    12,1  <br/>
- Utilização de Patch Panel e conectores RJ-45 fêmea de cat. Superior;
- Respeito as normas de comprimento;
- Boas práticas na conectorização
  - Destrançar o mínimo necessário;
  - Evitar o reaproveitamento dos conectores RJ-45 fêmea;
- Cuidados com as curvaturas dos cabos

![image](https://user-images.githubusercontent.com/66855310/135657458-5aafe027-2988-4a18-b6ab-f3fdfe1513fe.png)

- Cuidados na passagem dos cabos
  - Não estique;
  - Não torça;
  - Não amasse;
  - Não provoque nós;
- Cuidados na passagem dos cabos
  - Utilize, preferencialmente, cintas velcro para organizar os cabos;
  - Utilize estruturas de passagem adequadas que não forcem curvaturas acentuadas;
  - Deixe uma sobra técnica nas estruturas de passagem para futuros lançamentos de cabos;
- Cuidados na passagem dos cabos
  - Utilize o cabo guia, de nylon, para passar o arame de puxamento;
  - Depois, utilize o arame para puxar os cabos;
- Diminuir o número de conexões caso a perda de retorno esteja fora dos limites e outras medidas não resolveram o problema;
- Nunca derivar um cabo par trançado;
- Nunca emendar um cabo par trançado;
- Nunca “descascar” um fio de cabo par trançado (Conexões por engate rápido);
- Uso de ferramentas adequadas
  - Alicate de crimpar RJ-45 macho;
  - Decapador de cabo par trançado;
  - Alicate de impacto tipo push;
  - Estilete grande;
  - Tesoura de cabista;



 
























 





































# Autor
Marcelo Fabio Louzeiro B. <br/>
https://www.linkedin.com/in/marcelo-fabio-a04811191/
