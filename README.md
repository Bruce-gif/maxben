# maxben
maxben
#include <stdio.h>
#include <time.h>   
#include <stdlib.h>
int main()
{
	int dor, lugardor, escalador, naodor, respiracao, comer, pergunta, satisfeito, socorros, senha, senhaagr;
	printf("Ola, eu sou maxbem, seu agente pessoal, virtual, de saude\n");
	printf("Qual e' o seu nome?\n");
	char nome[100];
 	scanf("%s", nome);
	printf("ola %s\n", nome);
	printf("%s voce quer um consulta ou guia de primeiros socorros (1-consulta, 2-primeiros socorros)? ", nome);
	scanf("%d", &pergunta);
	if(pergunta == 2)
	        {
	printf("%s qual tipo de primeiros socorros voce precisa\n (1-infarto do miocardio\n 2-Choque elétrico\n 3-Desmaio\n 4-convulsao\n 5-alccolismo agudo\n 6-lesoes de tecidos moles\n 7-esmagamentos\n 8-amputacao\n 9-queimadura termica\n 10-queimadura quimica\n 11-queimadura eletrica\n 12-queimadura por frio\n 13-mordedura de animais\n 14-intoxicacao medicamentosa\n 15-plantas venenosas\n 16-acidentes com animais venenosos e peconhentos\n 17-acidentes radioativos\n 18-partos de emergencia)? "); 
	scanf("%d", &socorros);
	if(socorros == 1) printf("características:\n a)Dor angustiante e insuportavel na regiao precordial (subesternal),retroesternal e face anterior do torax.\n b) Compressão no peito e angustia, constricao.\n c) Duracao maior que 30 minutos.\n d) Dor nao diminui com repouso.\n e) Irradiacao no sentido da mandibula e membros superiores,\n Primeiros socorros:\n Procurar socorro medico ou um hospital com urgencia.\n Nao movimentar muito a vitima. O movimento ativa as emocoes e faz com que o coracao seja mais solicitado.\n Observar com precisao os sinais vitais.\n Manter a pessoa deitada, em repouso absoluto na posicao mais confortavel, em ambiente calmo e ventilado.\n Obter um breve relato da vitima ou de testemunhas sobre detalhes dos acontecimentos.\n Tranquilizar a vitima, procurando inspirar-lhe confianca e seguranca.\n Afrouxar as roupas.\n Evitar a ingestao de liquidos ou alimentos.\n No caso de parada cardiaca aplicar as tecnicas de ressuscitaçao cardio-respiratoria.\n Ver se a vitima traz nos bolsos remedios de urgencia medicamentos segundo as bulas, desde que a vitima esteja consciente.");
printf("A confirmacaoo da suspeita de quadro clinico de um infarto agudo do miocardio so ocorre com a utilizacao de exames complementares, tipo eletrocardiograma (ECG) e exames sanguineos (transaminase, etc), que deverao ser feitos no local do atendimento especializado\n");       
		} 
	if(pergunta == 1)
  {
	printf("voce esta sentindo alguma dor(1=sim, 2=nao)? ");
	scanf("%d", &dor);
	if(dor == 1)
	 {
	printf("De 0 a 10, o quanto de dor voce esta sentindo? ");
	scanf("%d", &escalador);
	if(escalador < 5) printf("entendo..\n");
	if(escalador >= 5) printf("entendo..\n");
	if(escalador > 10 || escalador < 1) printf("entendo..\n");
	printf("aonde esta doendo\n (1-barriga\n 2-cabeca\n 3-pescoco\n 4-pernas e pe'\n 5-bracos e maos\n 6-tudo\n 7-dente\n 8-garganta\n 9-pulmao\n 10-costas)? ");
	scanf("%d", &lugardor);
	if(lugardor == 1) printf("%s, e' recomendado que voce repouse na cama, de barriga para baixo!! Caso a dor persista depois de um dia repousando, procure um medico, e um medicamento(como Buscopan)\n", nome);
	if(lugardor == 2) printf("%s, e' recomendado que voce repouse na cama e descanse bem!! Caso a dor persista depois de dois dias repousando, procure um medico, e um medicamento(como Tylenol)\n", nome);
	if(lugardor == 3) printf("%s, e' recomendado que voce repouse e passe uma pomada para dor (como cataflan (pomada))! Caso a dor persista depois de dois dias procure um medico\n", nome);
	if(lugardor == 4) printf("%s, e' recomendado que voce repouse na cama!! Caso a dor persista depois de dois dias repousando, procure um medico\n", nome);
	if(lugardor == 5) printf("%s, e' recomendado que voce repouse na cama!! Caso a dor persista depois de dois dias repousando, procure um medico\n", nome);
	if(lugardor == 6) printf("%s, e' recomendado que voce va ao medico, pois esta com sintomas de gripe\n", nome);
	if(lugardor == 7) printf("%s, e' recomendado que voce descanse e use um remedio para dor (como Novalgina). Caso a dor persista depois de dois dias descansando, procure um medico ou um dentista\n", nome);
	if(lugardor == 8) printf("%s, e' recomendado que voce beba um copo d'agua com mel ou usar propolis, caso a dor persista procure um medico!\n", nome);
	if(lugardor == 9) printf("%s, e' recomendado que voce va ao medico, pois esta com sintomas de pneumonia, e e' recomendado um teste para covid-19\n", nome);																									
	if(lugardor == 10) printf("%s, e' recomendado que voce relaxe, massageie o local dolorido, use o calor para amenizar a dor, se a dor persistir, procure um medico, e tome remedio (como nervcaml wp lab)\n", nome);
	if(lugardor > 10) printf("me desculpe %s, nao tenho recomendacoes, caso precise de ajuda, consulte um medico\n", nome);
	 }
	if(dor == 2)
	 {
	printf("Oque voce esta se sentindo(1-mal estar 2-cansaco 3-nao sei explicar)? ");
	scanf("%d", &naodor);
	if(naodor == 1) printf("%s, repouse, beba bastante agua, e consulte um medico\n", nome);
	if(naodor == 2) printf("%s repouse, beba bastante agua, e consulte um medico\n", nome);
	if(naodor == 3) 
	    {
	printf("%s como esta sua respiracao \n(1-normal\n 2-dificil)? ", nome);
	scanf("%d", &respiracao);
	if(respiracao == 1) printf("Ok..\n");
	if(respiracao == 2) printf("Ok..\n");
	if(respiracao > 2) printf("me desculpe, nao tenho recomendacoes, caso precise de ajuda, consulte um medico\n");
	printf("%s voce anda comendo normalmente (1-sim 2-nao)? ", nome);
	scanf("%d", &comer);
	if(comer == 1) printf("ok..\n");
	if(comer == 2) printf("ok..\n");
	if(comer + respiracao == 2) printf("%s voce esta normal, mas caso continue se sentindo desconfortavel, procure um medico\n", nome);
	if(comer + respiracao == 4) printf("%s voce deve consultar um medico o mais rapido possivel!\n", nome);
	if(comer + respiracao == 3) printf("%s descanse, caso os sintomas persistirem procure um medico\n", nome);
	    }
	if(naodor > 3 || naodor < 0) printf("me desculpe %s, nao tenho recomendacoes, caso precise de ajuda, consulte um medico\n", nome);
	  }
	if(dor > 2 || dor <= 0) printf("me desculpe %s, nao tenho recomendacoes, caso precise de ajuda, consulte um medico\n", nome);
	}
int n;
printf("voce esta satisfeito(1-sim, 2- nao)? ");
scanf("%d", &n);
while(n == 2)
{
printf("Do que voce precisa(1-consulta, 2-primeiros socorros)? ");
int precisa; scanf("%d", &precisa);
if(precisa == 1){
printf("voce esta sentindo alguma dor(1=sim, 2=nao)? ");
	scanf("%d", &dor);
	if(dor == 1)
	 {
	printf("De 0 a 10, o quanto de dor voce esta sentindo? ");
	scanf("%d", &escalador);
	if(escalador < 5) printf("entendo..\n");
	if(escalador >= 5) printf("entendo..\n");
	if(escalador > 10 || escalador < 1) printf("entendo..\n");
	printf("aonde esta doendo\n (1-barriga\n 2-cabeca\n 3-pescoco\n 4-pernas e pe'\n 5-bracos e maos\n 6-tudo\n 7-dente\n 8-garganta\n 9-pulmao\n 10-costas)? ");
	scanf("%d", &lugardor);
	if(lugardor == 1) printf("%s, e' recomendado que voce repouse na cama, de barriga para baixo!! Caso a dor persista depois de um dia repousando, procure um medico, e um medicamento(como Buscopan)\n", nome);
	if(lugardor == 2) printf("%s, e' recomendado que voce repouse na cama e descanse bem!! Caso a dor persista depois de dois dias repousando, procure um medico, e um medicamento(como Tylenol)\n", nome);
	if(lugardor == 3) printf("%s, e' recomendado que voce repouse e passe uma pomada para dor (como cataflan (pomada))! Caso a dor persista depois de dois dias procure um medico\n", nome);
	if(lugardor == 4) printf("%s, e' recomendado que voce repouse na cama!! Caso a dor persista depois de dois dias repousando, procure um medico\n", nome);
	if(lugardor == 5) printf("%s, e' recomendado que voce repouse na cama!! Caso a dor persista depois de dois dias repousando, procure um medico\n", nome);
	if(lugardor == 6) printf("%s, e' recomendado que voce va ao medico, pois esta com sintomas de gripe\n", nome);
	if(lugardor == 7) printf("%s, e' recomendado que voce descanse e use um remedio para dor (como Novalgina). Caso a dor persista depois de dois dias descansando, procure um medico ou um dentista\n", nome);
	if(lugardor == 8) printf("%s, e' recomendado que voce beba um copo d'agua com mel ou usar propolis, caso a dor persista procure um medico!\n", nome);
	if(lugardor == 9) printf("%s, e' recomendado que voce va ao medico, pois esta com sintomas de pneumonia, e e' recomendado um teste para covid-19\n", nome);																									
	if(lugardor == 10) printf("%s, e' recomendado que voce relaxe, massageie o local dolorido, use o calor para amenizar a dor, se a dor persistir, procure um medico, e tome remedio (como nervcaml wp lab)\n", nome);
	if(lugardor > 10) printf("me desculpe %s, nao tenho recomendacoes, caso precise de ajuda, consulte um medico\n", nome);
	 }
	if(dor == 2)
	 {
	printf("Oque voce esta se sentindo(1-mal estar 2-cansaco 3-nao sei explicar)? ");
	scanf("%d", &naodor);
	if(naodor == 1) printf("%s, repouse, beba bastante agua, e consulte um medico\n", nome);
	if(naodor == 2) printf("%s repouse, beba bastante agua, e consulte um medico\n", nome);
	if(naodor == 3) 
	    {
	printf("%s como esta sua respiracao \n(1-normal\n 2-dificil)? ", nome);
	scanf("%d", &respiracao);
	if(respiracao == 1) printf("Ok..\n");
	if(respiracao == 2) printf("Ok..\n");
	if(respiracao > 2) printf("me desculpe, nao tenho recomendacoes, caso precise de ajuda, consulte um medico\n");
	printf("%s voce anda comendo normalmente (1-sim 2-nao)? ", nome);
	scanf("%d", &comer);
	if(comer == 1) printf("ok..\n");
	if(comer == 2) printf("ok..\n");
	if(comer + respiracao == 2) printf("%s voce esta normal, mas caso continue se sentindo desconfortavel, procure um medico\n", nome);
	if(comer + respiracao == 4) printf("%s voce deve consultar um medico o mais rapido possivel!\n", nome);
	if(comer + respiracao == 3) printf("%s descanse, caso os sintomas persistirem procure um medico\n", nome);
	    }
	if(naodor > 3 || naodor < 0) printf("me desculpe %s, nao tenho recomendacoes, caso precise de ajuda, consulte um medico\n", nome);
	  }
	if(dor > 2 || dor <= 0) printf("me desculpe %s, nao tenho recomendacoes, caso precise de ajuda, consulte um medico\n", nome);
	  }
if(precisa == 2){
printf("%s qual tipo de primeiros socorros voce precisa\n (1-infarto do miocardio\n 2-Choque elétrico\n 3-Desmaio\n 4-convulsao\n 5-alccolismo agudo\n 6-lesoes de tecidos moles\n 7-esmagamentos\n 8-amputacao\n 9-queimadura termica\n 10-queimadura quimica\n 11-queimadura eletrica\n 12-queimadura por frio\n 13-mordedura de animais\n 14-intoxicacao medicamentosa\n 15-plantas venenosas\n 16-acidentes com animais venenosos e peconhentos\n 17-acidentes radioativos\n 18-partos de emergencia)? ",nome);
 
                }
printf("voce esta satisfeito? ");
scanf("%d", &n);

}

printf("muito bem %s, voce foi um bom paciente!", nome);

	
   
	
return 0;
}
