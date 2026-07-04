# brazil_nehody.csv

Records of traffic accidents on federal highways in Brazil, 2007-2023 (each year is one CSV file).
Column names and their contents are self-explanatory (in Portuguese), possibly with exception:

* Dados_PRF_YYYY
  - br: number of federal highway (in fact, their codes are BR-XXX)
  - uf: state (estado) abbreviation
  - km: distance from the startpoint (km 0), where on the border between states the counting resets and starts from 0 again
  - regional, delegacia, uop: encoding of the record for official use
* Dados_Radares
  - velocidade_pesado: maximum allowed speed for big vehicles (trucks, buses etc.)
  - velocicade_leve: maximum allowed speed for small vehicles (bikes, cars etc.)