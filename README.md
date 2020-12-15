Repositório do Trabalho de Conclusão de Curso "Sintetizando um som de gaita utilizando _Python_"
=====

Neste repositório _online_ se encontram os códigos utilizados no TCC "Sintetização de um som de gaita utilizando _Python_" do concluinte David da Silva Cavalcante da Universidade Federal de Pernambuco. Uma parte dos códigos utilizados são baseados na ferramenta [_sms-tools_](https://github.com/MTG/sms-tools), desenvolvida pelo grupo de pesquisa [_Music Technologic Group_](https://www.upf.edu/web/mtg) da Universidade Pompeu Fabra de Barcelona. Mais informações sobre a ferramenta no próprio repositório ou no site da [ferramenta _sms-tools_](https://www.upf.edu/web/mtg/sms-tools). A parte do código para a emulação proposta pelo autor é de autoria do mesmo.

# Organização do repositório

```
codigo/ -> pasta com os codigos utilizados no trabalho

    sms-tools/ -> pasta com os códigos da ferramenta sms-tools
        |- dftModel.py -> funções de análise discreta de Fourier
        |- sineModel.py -> funções de análise e síntese do modelo senoidal
        |- sineModel_exp.ipynb -> jupyter notebook que executa o experimento
        |- sineModel_function.py -> função principal para sintetização do som
        |- utilFunctions.py -> funções úteis para execução da sintetização
        |- gaita_sint.wav -> resultado final da sintetização do som

    emulacao/ -> pasta com códigos da emulação proposta pelo autor
        |- emulacao_gaita.ipynb -> jupyter notebook com todo o código de emulação

resultados/ -> pasta com os áudios resultantes dos dois processos

    |- gaita_sint_sms-tools.wav -> áudio da sintetização pelo sms-tools
    |- gaita_emu_A.wav -> áudio da emulação da nota A (Lá)
    |- gaita_emu_B.wav -> áudio da emulação da nota B (Si)
    |- gaita_emu_C.wav -> áudio da emulação da nota C (Dó)
    |- gaita_emu_D.wav -> áudio da emulação da nota D (Ré)
    |- gaita_emu_E.wav -> áudio da emulação da nota E (Mi)
    |- gaita_emu_F.wav -> áudio da emulação da nota F (Fá)
    |- gaita_emu_G.wav -> áudio da emulação da nota G (Sol)

gaita.wav -> som utilizado como entrada para o processo de sintetização
```


# Licença

Os códigos da ferramenta [_sms-tools_](https://github.com/MTG/sms-tools) são _open-source_ e estão disponíveis de acordo com a Licença [_Affero GPL_](https://www.gnu.org/licenses/agpl-3.0.pt-br.html).

Os códigos desenvolvidos pelo autor do trabalho podem ser utilizados sem necessidade de aviso prévio contanto que não seja para fins lucrativos.