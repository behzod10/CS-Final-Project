#include <iostream>
#include <cstdlib>
#include <ctime>
using namespace std;

int main () {

    srand(time(NULL));

    //Finals
    int R1game1F;
    int R1game2F;
    string FR1game1F;
    string FR1game2F;

    //Third place
    int R1game1T;
    int R1game2T;
    string FR1game1T;
    string FR1game2T;

    //Semi-Finals
    int SFgame1;
    int SFgame2;
    int SFgame3;
    int SFgame4;
    string FSFgame1;
    string FSFgame2;
    string FSFgame3;
    string FSFgame4;

    //Quarter-Finals
    int QFgame1;
    int QFgame2;
    int QFgame3;
    int QFgame4;
    int QFgame5;
    int QFgame6;
    int QFgame7;
    int QFgame8;
    string FQFgame1;
    string FQFgame2;
    string FQFgame3;
    string FQFgame4;
    string FQFgame5;
    string FQFgame6;
    string FQFgame7;
    string FQFgame8;

    //Qualified teams
    
    //Qulified in 1st place from group A
    int Q1groupA;
    string FQ1groupA;

    //Qualified in 2nd place from group A
    int Q2groupA;
    string FQ2groupA;

    //Qulified in 1st place from group B
    int Q1groupB;
    string FQ1groupB;

    //Qualified in 2nd place from group B
    int Q2groupB;
    string FQ2groupB;

    //Qulified in 1st place from group C
    int Q1groupC;
    string FQ1groupC;

    //Qualified in 2nd place from group C
    int Q2groupC;
    string FQ2groupC;

    //Qulified in 1st place from group D
    int Q1groupD;
    string FQ1groupD;

    //Qualified in 2nd place from group D
    int Q2groupD;
    string FQ2groupD;

    //Qulified in 1st place from group E
    int Q1groupE;
    string FQ1groupE;

    //Qualified in 2nd place from group E
    int Q2groupE;
    string FQ2groupE;

    //Qulified in 1st place from group F
    int Q1groupF;
    string FQ1groupF;

    //Qualified in 2nd place from group F
    int Q2groupF;
    string FQ2groupF;

    //Qulified in 1st place from group G
    int Q1groupG;
    string FQ1groupG;

    //Qualified in 2nd place from group G
    int Q2groupG;
    string FQ2groupG;

    //Qulified in 1st place from group H
    int Q1groupH;
    string FQ1groupH;

    //Qualified in 2nd place from group H
    int Q2groupH;
    string FQ2groupH;
    
    
    //Qualified teams' attack, midfield, deffence, factor of unexpectancy, currency in Euros, popuplation, # of goals score in last 5 games, # of goals conceded in last 5 games, # of victories in last 5 games, # of defeats in last 5 games of round 1
    int Q1groupAattack, Q1groupBattack, Q1groupCattack, Q1groupDattack, Q1groupEattack, Q1groupFattack, Q1groupGattack, Q1groupHattack, Q2groupAattack, Q2groupBattack, Q2groupCattack, Q2groupDattack, Q2groupEattack, Q2groupFattack, Q2groupGattack, Q2groupHattack;
    int Q1groupAmidfield, Q1groupBmidfield, Q1groupCmidfield, Q1groupDmidfield, Q1groupEmidfield, Q1groupFmidfield, Q1groupGmidfield, Q1groupHmidfield, Q2groupAmidfield, Q2groupBmidfield, Q2groupCmidfield, Q2groupDmidfield, Q2groupEmidfield, Q2groupFmidfield, Q2groupGmidfield, Q2groupHmidfield;
    int Q1groupAdeffence, Q1groupBdeffence, Q1groupCdeffence, Q1groupDdeffence, Q1groupEdeffence, Q1groupFdeffence, Q1groupGdeffence, Q1groupHdeffence, Q2groupAdeffence, Q2groupBdeffence, Q2groupCdeffence, Q2groupDdeffence, Q2groupEdeffence, Q2groupFdeffence, Q2groupGdeffence, Q2groupHdeffence;
    int Q1groupAf, Q1groupBf, Q1groupCf, Q1groupDf, Q1groupEf, Q1groupFf, Q1groupGf, Q1groupHf, Q2groupAf, Q2groupBf, Q2groupCf, Q2groupDf, Q2groupEf, Q2groupFf, Q2groupGf, Q2groupHf;
    int Q1groupAcost, Q1groupBcost, Q1groupCcost, Q1groupDcost, Q1groupEcost, Q1groupFcost, Q1groupGcost, Q1groupHcost, Q2groupAcost, Q2groupBcost, Q2groupCcost, Q2groupDcost, Q2groupEcost, Q2groupFcost, Q2groupGcost, Q2groupHcost;
    int Q1groupApop, Q1groupBpop, Q1groupCpop, Q1groupDpop, Q1groupEpop, Q1groupFpop, Q1groupGpop, Q1groupHpop, Q2groupApop, Q2groupBpop, Q2groupCpop, Q2groupDpop, Q2groupEpop, Q2groupFpop, Q2groupGpop, Q2groupHpop;
    int Q1groupA5, Q1groupB5, Q1groupC5, Q1groupD5, Q1groupE5, Q1groupF5, Q1groupG5, Q1groupH5, Q2groupA5, Q2groupB5, Q2groupC5, Q2groupD5, Q2groupE5, Q2groupF5, Q2groupG5, Q2groupH5;
    int Q1groupAC5, Q1groupBC5, Q1groupCC5, Q1groupDC5, Q1groupEC5, Q1groupFC5, Q1groupGC5, Q1groupHC5, Q2groupAC5, Q2groupBC5, Q2groupCC5, Q2groupDC5, Q2groupEC5, Q2groupFC5, Q2groupGC5, Q2groupHC5;
    int Q1groupAV5, Q1groupBV5, Q1groupCV5, Q1groupDV5, Q1groupEV5, Q1groupFV5, Q1groupGV5, Q1groupHV5, Q2groupAV5, Q2groupBV5, Q2groupCV5, Q2groupDV5, Q2groupEV5, Q2groupFV5, Q2groupGV5, Q2groupHV5;
    int Q1groupAD5, Q1groupBD5, Q1groupCD5, Q1groupDD5, Q1groupED5, Q1groupFD5, Q1groupGD5, Q1groupHD5, Q2groupAD5, Q2groupBD5, Q2groupCD5, Q2groupDD5, Q2groupED5, Q2groupFD5, Q2groupGD5, Q2groupHD5;
    
    //Quarter-finals teams' attack, midfield, deffence, factor of unexpectancy, currency in Euros, popuplation, # of goals score in last 5 games, # of goals conceded in last 5 games, # of victories in last 5 games, # of defeats in last 5 games
    int QFgame1attack, QFgame2attack, QFgame3attack, QFgame4attack, QFgame5attack, QFgame6attack, QFgame7attack, QFgame8attack;
    int QFgame1midfield, QFgame2midfield, QFgame3midfield, QFgame4midfield, QFgame5midfield, QFgame6midfield, QFgame7midfield, QFgame8midfield;
    int QFgame1deffence, QFgame2deffence, QFgame3deffence, QFgame4deffence, QFgame5deffence, QFgame6deffence, QFgame7deffence, QFgame8deffence;
    int QFgame1f, QFgame2f, QFgame3f, QFgame4f, QFgame5f, QFgame6f, QFgame7f, QFgame8f;
    int QFgame1cost, QFgame2cost, QFgame3cost, QFgame4cost, QFgame5cost, QFgame6cost, QFgame7cost, QFgame8cost;
    int QFgame1pop, QFgame2pop, QFgame3pop, QFgame4pop, QFgame5pop, QFgame6pop, QFgame7pop, QFgame8pop;
    int QFgame15, QFgame25, QFgame35, QFgame45, QFgame55, QFgame65, QFgame75, QFgame85;
    int QFgame1C5, QFgame2C5, QFgame3C5, QFgame4C5, QFgame5C5, QFgame6C5, QFgame7C5, QFgame8C5;
    int QFgame1V5, QFgame2V5, QFgame3V5, QFgame4V5, QFgame5V5, QFgame6V5, QFgame7V5, QFgame8V5;
    int QFgame1D5, QFgame2D5, QFgame3D5, QFgame4D5, QFgame5D5, QFgame6D5, QFgame7D5, QFgame8D5;

    //Semi-finals teams' attack, midfield, deffence, factor of unexpectancy, currency in Euros, popuplation, # of goals score in last 5 games, # of goals conceded in last 5 games, # of victories in last 5 games, # of defeats in last 5 games
    int SFgame1attack, SFgame2attack, SFgame3attack, SFgame4attack;
    int SFgame1midfield, SFgame2midfield, SFgame3midfield, SFgame4midfield;
    int SFgame1deffence, SFgame2deffence, SFgame3deffence, SFgame4deffence;
    int SFgame1f, SFgame2f, SFgame3f, SFgame4f;
    int SFgame1cost, SFgame2cost, SFgame3cost, SFgame4cost;
    int SFgame1pop, SFgame2pop, SFgame3pop, SFgame4pop;
    int SFgame15, SFgame25, SFgame35, SFgame45;
    int SFgame1C5, SFgame2C5, SFgame3C5, SFgame4C5;
    int SFgame1V5, SFgame2V5, SFgame3V5, SFgame4V5;
    int SFgame1D5, SFgame2D5, SFgame3D5, SFgame4D5;

    //Finals teams' attack, midfield, deffence, factor of unexpectancy, currency in Euros, popuplation, # of goals score in last 5 games, # of goals conceded in last 5 games, # of victories in last 5 games, # of defeats in last 5 games
    int R1game1Fattack, R1game2Fattack;
    int R1game1Fmidfield, R1game2Fmidfield;
    int R1game1Fdeffence, R1game2Fdeffence;
    int R1game1Ff, R1game2Ff;
    int R1game1Fcost, R1game2Fcost;
    int R1game1Fpop, R1game2Fpop;
    int R1game1F5, R1game2F5;
    int R1game1FC5, R1game2FC5;
    int R1game1FV5, R1game2FV5;
    int R1game1FD5, R1game2FD5;

    //Match for third place teams' attack, midfield, deffence, factor of unexpectancy, currency in Euros, popuplation, # of goals score in last 5 games, # of goals conceded in last 5 games, # of victories in last 5 games, # of defeats in last 5 games
    int R1game1Tattack, R1game2Tattack;
    int R1game1Tmidfield, R1game2Tmidfield;
    int R1game1Tdeffence, R1game2Tdeffence;
    int R1game1Tf, R1game2Tf;
    int R1game1Tcost, R1game2Tcost;
    int R1game1Tpop, R1game2Tpop;
    int R1game1T5, R1game2T5;
    int R1game1TC5, R1game2TC5;
    int R1game1TV5, R1game2TV5;
    int R1game1TD5, R1game2TD5;

    //group A (Italy, Portugal, Australia, Iran)

    int portugal = 0, italy = 0, australia = 0, iran = 0;
    
    int italyattack = 90;
    int portugalattack = 82;
    int australiaattack = 85;
    int iranattack = 81;

    int italymidfield = 92;
    int portugalmidfield = 83;
    int australiamidfield = 81;
    int iranmidfield = 83;

    int italydeffence = 85;
    int portugaldeffence = 81;
    int australiadeffence = 79;
    int irandeffence = 75;

    //factor of unexpectancy
    int fportugal = rand() % 100;
    int fitaly = rand() % 100;
    int faustralia = rand() % 100;
    int firan = rand() % 100;
    
    //currency in Euros
    double italycost = 426000000;
    double portugalcost = 466000000;
    double australiacost = 46000000;
    double irancost = 43000000;

    //popuplation
    double italypop = 59257878;
    double portugalpop = 10274947;
    double australiapop = 24912343;
    double iranpop = 24912343;

    

    //# of goals score in last 5 games
    int italy5 = 3;
    int portugal5 = 8;
    int australia5 = 9;
    int iran5 = 6;

    //# of goals conceded in last 5 games
    int italyC5 = 2;
    int portugalC5 = 4;
    int australiaC5 = 4;
    int iranC5 = 3;

    //# of victories in last 5 games
    int italyV5 = 2;
    int portugalV5 = 3;
    int australiaV5 = 2;
    int iranV5 = 3;

    //# of defeats in last 5 games
    int italyD5 = 1;
    int portugalD5 = 0;
    int australiaD5 = 1;
    int iranD5 = 0;

    //group B (Croatia, Belgium, Denmark, Columbia)

    int croatia = 0, belgium = 0, denmark = 0, columbia = 0;

    int croatiaattack = 87;
    int belgiumattack = 89;
    int denmarkattack = 83;
    int columbiaattack = 85;

    int croatiamidfield = 90;
    int belgiummidfield = 89;
    int denmarkmidfield = 83;
    int columbiamidfield = 86;

    int croatiadeffence = 87;
    int belgiumdeffence = 88;
    int denmarkdeffence = 84;
    int columbiadeffence = 82;

    //factor of unexpectancy
    int fcroatia = rand() % 100;
    int fbelgium = rand() % 100;
    int fdenmark = rand() % 100;
    int fcolumbia = rand() % 100;

    //currency in Euros
    double croatiacost = 355000000;
    double belgiumcost = 756000000;
    double denmarkcost = 262000000;
    double columbiacost = 256000000;
    
    //popuplation
    double croatiapop = 4153818;
    double belgiumpop = 11527032;
    double denmarkpop = 5763620;
    double columbiapop = 49635457;
    
    

    //# of goals score in last 5 games
    int croatia5 = 6;
    int belgium5 = 10;
    int denmark5 = 6;
    int columbia5 = 10;

    //# of goals conceded in last 5 games
    int croatiaC5 = 11;
    int belgiumC5 = 7;
    int denmarkC5 = 1;
    int columbiaC5 = 5;

    //# of victories in last 5 games
    int croatiaV5 = 2;
    int belgiumV5 = 3;
    int denmarkV5 = 3;
    int columbiaV5 = 3;

    //# of defeats in last 5 games
    int croatiaD5 = 2;
    int belgiumD5 = 1;
    int denmarkD5 = 0;
    int columbiaD5 = 1;

    //group C (Chile, Sweden, Netherlands, Mexico)

int chile = 0, sweden = 0, netherlands = 0, mexico = 0;

int chileattack = 85;
int swedenattack = 84;
int netherlandsattack = 92;
int mexicoattack = 87;

int chilemidfield = 80;
int swedenmidfield = 85;
int netherlandsmidfield = 86;
int mexicomidfield = 84;

int chiledeffence = 75;
int swedendeffence = 80;
int netherlandsdeffence = 85;
int mexicodeffence = 80;

//group D (Wales, Poland, USA, Peru)

int wales = 0, poland = 0, usa = 0, peru = 0;

int walesattack = 70;
int polandattack = 70;
int usaattack = 65;
int peruattack = 75;

int walesmidfield = 70;
int polandmidfield = 75;
int usamidfield = 68;
int perumidfield = 75;

int walesdeffence = 72;
int polanddeffence = 79;
int usadeffence = 80;
int perudeffence = 78;
 
 //group E (Brazil, Germany, Senegal, Austria)

 int brazil = 0, germany = 0, senegal = 0, austria = 0;

 int brazilattack = 90;
 int germanyattack = 95;
 int senegalattack = 70;
 int austriaattack = 75;

 int brazilmidfield = 95;
 int germanymidfield = 90;
 int senegalmidfield = 88;
 int austriamidfield = 80;

 int brazildeffence = 90;
 int germanydeffence = 95;
 int senegaldeffence = 90;
 int austriadeffence = 75;

 //group F (Romania, Iceland, England, Spain)

 int romania = 0, iceland = 0, england = 0, spain = 0;

 int romaniaattack = 78;
 int icelandattack = 75;
 int englandattack = 90;
 int spainattack = 90;

 int romaniamidfield = 75;
 int icelandmidfield = 80;
 int englandmidfield = 93;
 int spainmidfield = 95;

 int romaniadeffence = 80;
 int icelanddeffence = 79;
 int englanddeffence = 90;
 int spaindeffence = 95;

 //group G (Argentina, France, Turkey, Russia) 

 int argentina = 0, france = 0, turkey = 0, russia = 0

 int argentinaattack = 95;
 int franceattack = 95;
 int turkeyattack = 70;
 int russiaattack = 70;

 int argentinamidfield = 90;
 int francemidfield = 95;
 int turkeymidfield = 92;
 int russiamidfield = 80;

 int argentinadeffence = 90;
 int francedeffence = 90;
 int turkeydeffence = 80;
 int russiadeffence = 70;

 //group H (Uruguay, Serbia, Venezuela, Morocco)

 int uruguay = 0, serbia = 0, venezuela = 0, morocco = 0;

 int uruguayattack = 90;
 int serbiaattack = 60;
 int venezuelaattack = 80;
 int moroccoattack = 70;

 int uruguaymidfield = 85;
 int serbiamidfield = 90;
 int venezuelamidfield = 70;
 int moroccomidfield = 70;

 int uruguaydeffence = 80;
 int serbiadeffence = 80;
 int venezueladeffence = 80;
 int moroccodeffence = 75;

    //group B

    //attack of croatia
    if (croatiaattack > belgiumattack) {
        croatia += 1;
    }
    
    if (croatiaattack > denmarkattack) {
        croatia += 1;
    }

    if (croatiaattack > columbiaattack) {
        croatia += 1;
    }

    //attack of belgium
    if (belgiumattack > croatiaattack) {
        belgium += 1;
    }

    if (belgiumattack > denmarkattack) {
        belgium += 1;
    }

    if (belgiumattack > columbiaattack) {
        belgium += 1;
    }

    //attack of denmark
    if (denmarkattack > belgiumattack) {
        denmark += 1;
    }

    if (denmarkattack > croatiaattack) {
        denmark += 1;
    }

    if (denmarkattack > columbiaattack) {
        denmark += 1;
    }

    //attack of columbia
    if (columbiaattack > denmarkattack) {
        columbia += 1;
    }

    if (columbiaattack > belgiumattack) {
        columbia += 1;
    }

    if (columbiaattack > croatiaattack) {
        columbia += 1;
    }

    //midfield of croatia
    if (croatiamidfield > belgiummidfield) {
        croatia += 1;
    }
    
    if (croatiamidfield > denmarkmidfield) {
        croatia += 1;
    }

    if (croatiamidfield > columbiamidfield) {
        croatia += 1;
    }

    //midfield of belgium
    if (belgiummidfield > denmarkmidfield) {
        belgium += 1;
    }
    
    if (belgiummidfield > columbiamidfield) {
        belgium += 1;
    }

    if (belgiummidfield > croatiamidfield) {
        belgium += 1;
    }

    //midfield of denmark
    if (denmarkmidfield > columbiamidfield) {
        denmark += 1;
    }
    
    if (denmarkmidfield > croatiamidfield) {
        denmark += 1;
    }

    if (denmarkmidfield > belgiummidfield) {
        denmark += 1;
    }

    //midfield of columbia
    if (columbiamidfield > denmarkmidfield) {
        columbia += 1;
    }
    
    if (columbiamidfield > croatiamidfield) {
        columbia += 1;
    }

    if (columbiamidfield > belgiummidfield) {
        columbia += 1;
    }

    //deffence of denmark
    if (denmarkdeffence > croatiadeffence) {
        denmark += 1;
    }
    
    if (denmarkdeffence > belgiumdeffence) {
        denmark += 1;
    }

    if (denmarkdeffence > columbiadeffence) {
        denmark += 1;
    }

    //deffence of croatia
    if (croatiadeffence > columbiadeffence) {
        croatia += 1;
    }
    
    if (croatiadeffence > belgiumdeffence) {
        croatia += 1;
    }

    if (croatiadeffence > denmarkdeffence) {
        croatia += 1;
    }
    
    //deffence of belgium
    if (belgiumdeffence > denmarkdeffence) {
        belgium += 1;
    }
    
    if (belgiumdeffence > croatiadeffence) {
        belgium += 1;
    }

    if (belgiumdeffence > columbiadeffence) {
        belgium += 1;
    }

    //deffence of columbia
    if (columbiadeffence > belgiumdeffence) {
        columbia += 1;
    }
    
    if (columbiadeffence > croatiadeffence) {
        columbia += 1;
    }

    if (columbiadeffence > denmarkdeffence) {
        columbia += 1;
    }


    //cost of croatia
    if (croatiacost > belgiumcost) {
        croatia += 1;
    }
    
    if (croatiacost > denmarkcost) {
        croatia += 1;
    }

    if (croatiacost > columbiacost) {
        croatia += 1;
    }
    
    //cost of belgium
    if (belgiumcost > croatiacost) {
        belgium += 1;
    }
    
    if (belgiumcost > denmarkcost) {
        belgium += 1;
    }

    if (belgiumcost > columbiacost) {
        belgium += 1;
    }
    
    //cost of denmark
    if (denmarkcost > croatiacost) {
        denmark += 1;
    }
    
    if (denmarkcost > belgiumcost) {
        denmark += 1;
    }

    if (denmarkcost > columbiacost) {
        denmark += 1;
    }

    //cost of columbia
    if (columbiacost > croatiacost) {
        columbia += 1;
    }
    
    if (columbiacost > belgiumcost) {
        columbia += 1;
    }

    if (columbiacost > denmarkcost) {
        columbia += 1;
    }

    //population of columbia
    if (columbiapop > denmarkpop) {
        columbia += 1;
    }
    
    if (columbiapop > belgiumpop) {
        columbia += 1;
    }

    if (columbiapop > croatiapop) {
        columbia += 1;
    }

    //population of denmark
    if (denmarkpop > columbiapop) {
        denmark += 1;
    }
    
    if (denmarkpop > belgiumpop) {
        denmark += 1;
    }

    if (denmarkpop > croatiapop) {
        denmark += 1;
    }

    //population of belgium
    if (belgiumpop > columbiapop) {
        belgium += 1;
    }
    
    if (belgiumpop > denmarkpop) {
        belgium += 1;
    }

    if (belgiumpop > croatiapop) {
        belgium += 1;
    }

    //population of croatia
    if (croatiapop > columbiapop) {
        croatia += 1;
    }
    
    if (croatiapop > denmarkpop) {
        croatia += 1;
    }

    if (croatiapop > belgiumpop) {
        croatia += 1;
    }

    

    //croatia # of goals score in last 5 games
    if (croatia5 > belgium5) {
        croatia += 1;
    }
    
    if (croatia5 > denmark5) {
        croatia += 1;
    }

    if (croatia5 > columbia5) {
        croatia += 1;
    }

    //belgium # of goals score in last 5 games
    if (belgium5 > croatia5) {
        belgium += 1;
    }
    
    if (belgium5 > denmark5) {
        belgium += 1;
    }

    if (belgium5 > columbia5) {
        belgium += 1;
    }

    //denmark # of goals score in last 5 games
    if (denmark5 > croatia5) {
        denmark += 1;
    }
    
    if (denmark5 > belgium5) {
        denmark += 1;
    }

    if (denmark5 > columbia5) {
        denmark += 1;
    }

    //columbia # of goals score in last 5 games
    if (columbia5 > croatia5) {
        columbia += 1;
    }
    
    if (columbia5 > belgium5) {
        columbia += 1;
    }

    if (columbia5 > denmark5) {
        columbia += 1;
    }

    //columbia # of goals conceded in last 5 games
    if (columbiaC5 > denmarkC5) {
        columbia -= 1;
    }
    
    if (columbiaC5 > belgiumC5) {
        columbia -= 1;
    }

    if (columbiaC5 > croatiaC5) {
        columbia -= 1;
    }

    //denmark # of goals conceded in last 5 games
    if (denmarkC5 > columbiaC5) {
        denmark -= 1;
    }
    
    if (denmarkC5 > belgiumC5) {
        denmark -= 1;
    }

    if (denmarkC5 > croatiaC5) {
        denmark -= 1;
    }

    //belgium # of goals conceded in last 5 games
    if (belgiumC5 > columbiaC5) {
        belgium -= 1;
    }
    
    if (belgiumC5 > denmarkC5) {
        belgium -= 1;
    }

    if (belgiumC5 > croatiaC5) {
        belgium -= 1;
    }

    //croatia # of goals conceded in last 5 games
    if (croatiaC5 > columbiaC5) {
        croatia -= 1;
    }
    
    if (croatiaC5 > denmarkC5) {
        croatia -= 1;
    }

    if (croatiaC5 > belgiumC5) {
        croatia -= 1;
    }

    //croatia # of victories in last 5 games
    if (croatiaV5 > belgiumV5) {
        croatia += 1;
    }
    
    if (croatiaV5 > denmarkV5) {
        croatia += 1;
    }

    if (croatiaV5 > columbiaV5) {
        croatia += 1;
    }

    //belgium # of victories in last 5 games
    if (belgiumV5 > croatiaV5) {
        belgium += 1;
    }
    
    if (belgiumV5 > denmarkV5) {
        belgium += 1;
    }

    if (belgiumV5 > columbiaV5) {
        belgium += 1;
    }

    //denmark # of victories in last 5 games
    if (denmarkV5 > croatiaV5) {
        denmark += 1;
    }
    
    if (denmarkV5 > belgiumV5) {
        denmark += 1;
    }

    if (denmarkV5 > columbiaV5) {
        denmark += 1;
    }

    //columbia # of victories in last 5 games
    if (columbiaV5 > croatiaV5) {
        columbia += 1;
    }
    
    if (columbiaV5 > belgiumV5) {
        columbia += 1;
    }

    if (columbiaV5 > denmarkV5) {
        columbia += 1;
    }

    //columbia # of defeats in last 5 games
    if (columbiaD5 > denmarkD5) {
        columbia -= 1;
    }
    
    if (columbiaD5 > belgiumD5) {
        columbia -= 1;
    }

    if (columbiaD5 > croatiaD5) {
        columbia -= 1;
    }

    //denmark # of defeats in last 5 games
    if (denmarkD5 > columbiaD5) {
        denmark -= 1;
    }
    
    if (denmarkD5 > belgiumD5) {
        denmark -= 1;
    }

    if (denmarkD5 > croatiaD5) {
        denmark -= 1;
    }

    //belgium # of defeats in last 5 games
    if (belgiumD5 > columbiaD5) {
        belgium -= 1;
    }
    
    if (belgiumD5 > denmarkD5) {
        belgium -= 1;
    }

    if (belgiumD5 > croatiaD5) {
        belgium -= 1;
    }

    //croatia # of defeats in last 5 games
    if (croatiaD5 > columbiaD5) {
        croatia -= 1;
    }
    
    if (croatiaD5 > denmarkD5) {
        croatia -= 1;
    }

    if (croatiaD5 > belgiumD5) {
        croatia -= 1;
    }

    //croatia factor of unexpectancy
    if (fcroatia > fbelgium) {
        croatia += 4;
    }
    
    if (fcroatia > fdenmark) {
        croatia += 4;
    }

    if (fcroatia > fcolumbia) {
        croatia += 4;
    }

    //belgium factor of unexpectancy
    if (fbelgium > fcroatia) {
        belgium += 4;
    }
    
    if (fbelgium > fdenmark) {
        belgium += 4;
    }

    if (fbelgium > fcolumbia) {
        belgium += 4;
    }

    //denmark factor of unexpectancy
    if (fdenmark > fcroatia) {
        denmark += 4;
    }
    
    if (fdenmark > fbelgium) {
        denmark += 4;
    }

    if (fdenmark > fcolumbia) {
        denmark += 4;
    }

    //columbia factor of unexpectancy
    if (fcolumbia > fcroatia) {
        columbia += 4;
    }
    
    if (fcolumbia > fbelgium) {
        columbia += 4;
    }

    if (fcolumbia > fdenmark) {
        columbia += 4;
    }

    
    
    //1st place results of group B
    if (columbia > denmark && columbia > croatia && columbia > belgium) {
        cout << "Columbia is the winner of Group B" << endl;
        Q1groupB = columbia;
        Q1groupBattack = columbiaattack;
        Q1groupBmidfield = columbiamidfield;
        Q1groupBdeffence = columbiadeffence;
        Q1groupBf = fcolumbia;
        Q1groupBcost = columbiacost;
        Q1groupBpop = columbiapop;
        Q1groupB5 = columbia5;
        Q1groupBC5 = columbiaC5;
        Q1groupBV5 = columbiaV5;
        Q1groupBD5 = columbiaD5;
        FQ1groupB = "Columbia";
    }

    else if (denmark > columbia && denmark > croatia && denmark > belgium) {
        cout << "Denmark is the winner of Group B" << endl;
        Q1groupB = denmark;
        Q1groupBattack = denmarkattack;
        Q1groupBmidfield = denmarkmidfield;
        Q1groupBdeffence = denmarkdeffence;
        Q1groupBf = fdenmark;
        Q1groupBcost = denmarkcost;
        Q1groupBpop = denmarkpop;
        Q1groupB5 = denmark5;
        Q1groupBC5 = denmarkC5;
        Q1groupBV5 = denmarkV5;
        Q1groupBD5 = denmarkD5;
        FQ1groupB = "Denmark";
    }

    else if (croatia > denmark && croatia > belgium && croatia > columbia) {
        cout << "Croatia is the winner of Group B" << endl;
        Q1groupB = croatia;
        Q1groupBattack = croatiaattack;
        Q1groupBmidfield = croatiamidfield;
        Q1groupBdeffence = croatiadeffence;
        Q1groupBf = fcroatia;
        Q1groupBcost = croatiacost;
        Q1groupBpop = croatiapop;
        Q1groupB5 = croatia5;
        Q1groupBC5 = croatiaC5;
        Q1groupBV5 = croatiaV5;
        Q1groupBD5 = croatiaD5;
        FQ1groupB = "Croatia";
    }

    else if (belgium > denmark && belgium > croatia && belgium > columbia) {
        cout << "Belgium is the winner of Group B" << endl;
        Q1groupB = belgium;
        Q1groupBattack = belgiumattack;
        Q1groupBmidfield = belgiummidfield;
        Q1groupBdeffence = belgiumdeffence;
        Q1groupBf = fbelgium;
        Q1groupBcost = belgiumcost;
        Q1groupBpop = belgiumpop;
        Q1groupB5 = belgium5;
        Q1groupBC5 = belgiumC5;
        Q1groupBV5 = belgiumV5;
        Q1groupBD5 = belgiumD5;
        FQ1groupB = "Belgium";
    }

    else {}
    
    
    //2nd place results of group B
   
    //Columbia
    if (columbia > denmark && columbia > croatia && columbia < belgium) {
        cout << "Columbia is the second of Group B" << endl;
        Q2groupB = columbia;
        Q2groupBattack = columbiaattack;
        Q2groupBmidfield = columbiamidfield;
        Q2groupBdeffence = columbiadeffence;
        Q2groupBf = fcolumbia;
        Q2groupBcost = columbiacost;
        Q2groupBpop = columbiapop;
        Q2groupB5 = columbia5;
        Q2groupBC5 = columbiaC5;
        Q2groupBV5 = columbiaV5;
        Q2groupBD5 = columbiaD5;
        FQ2groupB = "Columbia";
    }

    else if (columbia > denmark && columbia < croatia && columbia > belgium) {
        cout << "Columbia is the second of Group B" << endl;
        Q2groupB = columbia;
        Q2groupBattack = columbiaattack;
        Q2groupBmidfield = columbiamidfield;
        Q2groupBdeffence = columbiadeffence;
        Q2groupBf = fcolumbia;
        Q2groupBcost = columbiacost;
        Q2groupBpop = columbiapop;
        Q2groupB5 = columbia5;
        Q2groupBC5 = columbiaC5;
        Q2groupBV5 = columbiaV5;
        Q2groupBD5 = columbiaD5;
        FQ2groupB = "Columbia";
    }

    else if (columbia < denmark && columbia > croatia && columbia > belgium) {
        cout << "Columbia is the second of Group B" << endl;
        Q2groupB = columbia;
        Q2groupBattack = columbiaattack;
        Q2groupBmidfield = columbiamidfield;
        Q2groupBdeffence = columbiadeffence;
        Q2groupBf = fcolumbia;
        Q2groupBcost = columbiacost;
        Q2groupBpop = columbiapop;
        Q2groupB5 = columbia5;
        Q2groupBC5 = columbiaC5;
        Q2groupBV5 = columbiaV5;
        Q2groupBD5 = columbiaD5;
        FQ2groupB = "Columbia";
    }

    else {}

    //Denmark
    if (denmark > columbia && denmark > croatia && denmark < belgium) {
        cout << "Denmark is the second of Group B" << endl;
        Q2groupB = denmark;
        Q2groupBattack = denmarkattack;
        Q2groupBmidfield = denmarkmidfield;
        Q2groupBdeffence = denmarkdeffence;
        Q2groupBf = fdenmark;
        Q2groupBcost = denmarkcost;
        Q2groupBpop = denmarkpop;
        Q2groupB5 = denmark5;
        Q2groupBC5 = denmarkC5;
        Q2groupBV5 = denmarkV5;
        Q2groupBD5 = denmarkD5;
        FQ2groupB = "Denmark";
    }

    else if (denmark > columbia && denmark < croatia && denmark > belgium) {
        cout << "Denmark is the second of Group B" << endl;
        Q2groupB = denmark;
        Q2groupBattack = denmarkattack;
        Q2groupBmidfield = denmarkmidfield;
        Q2groupBdeffence = denmarkdeffence;
        Q2groupBf = fdenmark;
        Q2groupBcost = denmarkcost;
        Q2groupBpop = denmarkpop;
        Q2groupB5 = denmark5;
        Q2groupBC5 = denmarkC5;
        Q2groupBV5 = denmarkV5;
        Q2groupBD5 = denmarkD5;
        FQ2groupB = "Denmark";
    }

    else if (denmark < columbia && denmark > croatia && denmark > belgium) {
        cout << "Denmark is the second of Group B" << endl;
        Q2groupB = denmark;
        Q2groupBattack = denmarkattack;
        Q2groupBmidfield = denmarkmidfield;
        Q2groupBdeffence = denmarkdeffence;
        Q2groupBf = fdenmark;
        Q2groupBcost = denmarkcost;
        Q2groupBpop = denmarkpop;
        Q2groupB5 = denmark5;
        Q2groupBC5 = denmarkC5;
        Q2groupBV5 = denmarkV5;
        Q2groupBD5 = denmarkD5;
        FQ2groupB = "Denmark";
    }

    else {}

    //Croatia
    if (croatia > denmark && croatia > belgium && croatia < columbia) {
        cout << "Croatia is the second of Group B" << endl;
        Q2groupB = croatia;
        Q2groupBattack = croatiaattack;
        Q2groupBmidfield = croatiamidfield;
        Q2groupBdeffence = croatiadeffence;
        Q2groupBf = fcroatia;
        Q2groupBcost = croatiacost;
        Q2groupBpop = croatiapop;
        Q2groupB5 = croatia5;
        Q2groupBC5 = croatiaC5;
        Q2groupBV5 = croatiaV5;
        Q2groupBD5 = croatiaD5;
        FQ2groupB = "Croatia";
    }

    else if (croatia > denmark && croatia < belgium && croatia > columbia) {
        cout << "Croatia is the second of Group B" << endl;
        Q2groupB = croatia;
        Q2groupBattack = croatiaattack;
        Q2groupBmidfield = croatiamidfield;
        Q2groupBdeffence = croatiadeffence;
        Q2groupBf = fcroatia;
        Q2groupBcost = croatiacost;
        Q2groupBpop = croatiapop;
        Q2groupB5 = croatia5;
        Q2groupBC5 = croatiaC5;
        Q2groupBV5 = croatiaV5;
        Q2groupBD5 = croatiaD5;
        FQ2groupB = "Croatia";
    }

    else if (croatia < denmark && croatia > belgium && croatia > columbia) {
        cout << "Croatia is the second of Group B" << endl;
        Q2groupB = croatia;
        Q2groupBattack = croatiaattack;
        Q2groupBmidfield = croatiamidfield;
        Q2groupBdeffence = croatiadeffence;
        Q2groupBf = fcroatia;
        Q2groupBcost = croatiacost;
        Q2groupBpop = croatiapop;
        Q2groupB5 = croatia5;
        Q2groupBC5 = croatiaC5;
        Q2groupBV5 = croatiaV5;
        Q2groupBD5 = croatiaD5;
        FQ2groupB = "Croatia";
    }

    else {}

    //Belgium
    if (belgium > denmark && belgium > croatia && belgium < columbia) {
        cout << "Belgium is the second of Group B" << endl;
        Q2groupB = belgium;
        Q2groupBattack = belgiumattack;
        Q2groupBmidfield = belgiummidfield;
        Q2groupBdeffence = belgiumdeffence;
        Q2groupBf = fbelgium;
        Q2groupBcost = belgiumcost;
        Q2groupBpop = belgiumpop;
        Q2groupB5 = belgium5;
        Q2groupBC5 = belgiumC5;
        Q2groupBV5 = belgiumV5;
        Q2groupBD5 = belgiumD5;
        FQ2groupB = "Belgium";
    }

    else if (belgium > denmark && belgium < croatia && belgium > columbia) {
        cout << "Belgium is  the second of Group B" << endl;
        Q2groupB = belgium;
        Q2groupBattack = belgiumattack;
        Q2groupBmidfield = belgiummidfield;
        Q2groupBdeffence = belgiumdeffence;
        Q2groupBf = fbelgium;
        Q2groupBcost = belgiumcost;
        Q2groupBpop = belgiumpop;
        Q2groupB5 = belgium5;
        Q2groupBC5 = belgiumC5;
        Q2groupBV5 = belgiumV5;
        Q2groupBD5 = belgiumD5;
        FQ2groupB = "Belgium";
    }

    else if (belgium < denmark && belgium > croatia && belgium > columbia) {
        cout << "Belgium is the second of Group B" << endl;
        Q2groupB = belgium;
        Q2groupBattack = belgiumattack;
        Q2groupBmidfield = belgiummidfield;
        Q2groupBdeffence = belgiumdeffence;
        Q2groupBf = fbelgium;
        Q2groupBcost = belgiumcost;
        Q2groupBpop = belgiumpop;
        Q2groupB5 = belgium5;
        Q2groupBC5 = belgiumC5;
        Q2groupBV5 = belgiumV5;
        Q2groupBD5 = belgiumD5;
        FQ2groupB = "Belgium";
    }

    else {}

    cout << endl;

    //@@@@@@@

    //group A

    //attack of italy
    if (italyattack > portugalattack) {
        italy += 1;
    }
    
    if (italyattack > australiaattack) {
        italy += 1;
    }

    if (italyattack > iranattack) {
        italy += 1;
    }

    //attack of portugal
    if (portugalattack > italyattack) {
        portugal += 1;
    }

    if (portugalattack > australiaattack) {
        portugal += 1;
    }

    if (portugalattack > iranattack) {
        portugal += 1;
    }

    //attack of australia
    if (australiaattack > italyattack) {
        australia += 1;
    }

    if (australiaattack > portugalattack) {
        australia += 1;
    }

    if (australiaattack > iranattack) {
        australia += 1;
    }

    //attack of iran
    if (iranattack > italyattack) {
        iran += 1;
    }

    if (iranattack > portugalattack) {
        iran += 1;
    }

    if (iranattack > australiaattack) {
        iran += 1;
    }

    //midfield of italy
    if (italymidfield > portugalmidfield) {
        italy += 1;
    }
    
    if (italymidfield > australiamidfield) {
        italy += 1;
    }

    if (italymidfield > iranmidfield) {
        italy += 1;
    }

    //midfield of portugal
    if (portugalmidfield > italymidfield) {
        portugal += 1;
    }
    
    if (portugalmidfield > australiamidfield) {
        portugal += 1;
    }

    if (portugalmidfield > iranmidfield) {
        portugal += 1;
    }

    //midfield of australia
    if (australiamidfield > italymidfield) {
        australia += 1;
    }
    
    if (australiamidfield > portugalmidfield) {
        australia += 1;
    }

    if (australiamidfield > iranmidfield) {
        australia += 1;
    }

    //midfield of iran
    if (iranmidfield > italymidfield) {
        iran += 1;
    }
    
    if (iranmidfield > portugalmidfield) {
        iran += 1;
    }

    if (iranmidfield > australiamidfield) {
        iran += 1;
    }

    //deffence of italy
    if (italydeffence > portugaldeffence) {
        italy += 1;
    }
    
    if (italydeffence > australiadeffence) {
        italy += 1;
    }

    if (italydeffence > irandeffence) {
        italy += 1;
    }

    //deffence of portugal
    if (portugaldeffence > italydeffence) {
        portugal += 1;
    }
    
    if (portugaldeffence > australiadeffence) {
        portugal += 1;
    }

    if (portugaldeffence > irandeffence) {
        portugal += 1;
    }
    
    //deffence of australia
    if (australiadeffence > italydeffence) {
        australia += 1;
    }
    
    if (australiadeffence > portugaldeffence) {
        australia += 1;
    }

    if (australiadeffence > irandeffence) {
        australia += 1;
    }

    //deffence of iran
    if (irandeffence > italydeffence) {
        iran += 1;
    }
    
    if (irandeffence > portugaldeffence) {
        iran += 1;
    }

    if (irandeffence > australiadeffence) {
        iran += 1;
    }

    //cost of italy
    if (italycost > portugalcost) {
        italy += 1;
    }
    
    if (italycost > australiacost) {
        italy += 1;
    }

    if (italycost > irancost) {
        italy += 1;
    }

    //cost of portugal
    if (portugalcost > italycost) {
        portugal += 1;
    }
    
    if (portugalcost > australiacost) {
        portugal += 1;
    }

    if (portugalcost > irancost) {
        portugal += 1;
    }

    //cost of australia
    if (australiacost > italycost) {
        australia += 1;
    }
    
    if (australiacost > portugalcost) {
        australia += 1;
    }

    if (australiacost > irancost) {
        australia += 1;
    }

    //cost of iran
    if (irancost > italycost) {
        iran += 1;
    }
    
    if (irancost > portugalcost) {
        iran += 1;
    }

    if (irancost > australiacost) {
        iran += 1;
    }

    //population of iran
    if (iranpop > australiapop) {
        iran += 1;
    }
    
    if (iranpop > portugalpop) {
        iran += 1;
    }

    if (iranpop > italypop) {
        iran += 1;
    }

    //population of australia
    if (australiapop > iranpop) {
        australia += 1;
    }
    
    if (australiapop > portugalpop) {
        australia += 1;
    }

    if (australiapop > italypop) {
        australia += 1;
    }

    //population of portugal
    if (portugalpop > iranpop) {
        portugal += 1;
    }
    
    if (portugalpop > australiapop) {
        portugal += 1;
    }

    if (portugalpop > italypop) {
        portugal += 1;
    }

    //population of italy
    if (italypop > iranpop) {
        italy += 1;
    }
    
    if (italypop > australiapop) {
        italy += 1;
    }

    if (italypop > portugalpop) {
        italy += 1;
    }

    

    //italy # of goals score in last 5 games
    if (italy5 > portugal5) {
        italy += 1;
    }
    
    if (italy5 > australia5) {
        italy += 1;
    }

    if (italy5 > iran5) {
        italy += 1;
    }

    //portugal # of goals score in last 5 games
    if (portugal5 > italy5) {
        portugal += 1;
    }
    
    if (portugal5 > australia5) {
        portugal += 1;
    }

    if (portugal5 > iran5) {
        portugal += 1;
    }

    //australia # of goals score in last 5 games
    if (australia5 > italy5) {
        australia += 1;
    }
    
    if (australia5 > portugal5) {
        australia += 1;
    }

    if (australia5 > iran5) {
        australia += 1;
    }
    
    //iran # of goals score in last 5 games
    if (iran5 > italy5) {
        iran += 1;
    }
    
    if (iran5 > portugal5) {
        iran += 1;
    }

    if (iran5 > australia5) {
        iran += 1;
    }

    //iran # of goals conceded in last 5 games
    if (iranC5 > australiaC5) {
        iran -= 1;
    }
    
    if (iranC5 > portugalC5) {
        iran -= 1;
    }

    if (iranC5 > italyC5) {
        iran -= 1;
    }
    
    //australia # of goals conceded in last 5 games
    if (australiaC5 > iranC5) {
        australia -= 1;
    }
    
    if (australiaC5 > portugalC5) {
        australia -= 1;
    }

    if (australiaC5 > italyC5) {
        australia -= 1;
    }

    //portugal # of goals conceded in last 5 games
    if (portugalC5 > iranC5) {
        portugal -= 1;
    }
    
    if (portugalC5 > australiaC5) {
        portugal -= 1;
    }

    if (portugalC5 > italyC5) {
        portugal -= 1;
    }

    //italy # of goals conceded in last 5 games
    if (italyC5 > iranC5) {
        italy -= 1;
    }
    
    if (italyC5 > australiaC5) {
        italy -= 1;
    }

    if (italyC5 > portugalC5) {
        italy -= 1;
    }

    //italy # of goals victory in last 5 games
    if (italyV5 > portugalV5) {
        italy += 1;
    }
    
    if (italyV5 > australiaV5) {
        italy += 1;
    }

    if (italyV5 > iranV5) {
        italy += 1;
    }

    //portugal # of goals victory in last 5 games
    if (portugalV5 > italyV5) {
        portugal += 1;
    }
    
    if (portugalV5 > australiaV5) {
        portugal += 1;
    }

    if (portugalV5 > iranV5) {
        portugal += 1;
    }

    //australia # of goals victory in last 5 games
    if (australiaV5 > italyV5) {
        australia += 1;
    }
    
    if (australiaV5 > portugalV5) {
        australia += 1;
    }

    if (australiaV5 > iranV5) {
        australia += 1;
    }

    //iran # of goals victory in last 5 games
    if (iranV5 > italyV5) {
        iran += 1;
    }
    
    if (iranV5 > portugalV5) {
        iran += 1;
    }

    if (iranV5 > australiaV5) {
        iran += 1;
    }

    //iran # of defeats in last 5 games
    if (iranD5 > australiaD5) {
        iran -= 1;
    }
    
    if (iranD5 > portugalD5) {
        iran -= 1;
    }

    if (iranD5 > italyD5) {
        iran -= 1;
    }

    //australia # of defeats in last 5 games
    if (australiaD5 > iranD5) {
        australia -= 1;
    }
    
    if (australiaD5 > portugalD5) {
        australia -= 1;
    }

    if (australiaD5 > italyD5) {
        australia -= 1;
    }

    //portugal # of defeats in last 5 games
    if (portugalD5 > iranD5) {
        portugal -= 1;
    }
    
    if (portugalD5 > australiaD5) {
        portugal -= 1;
    }

    if (portugalD5 > italyD5) {
        portugal -= 1;
    }

    //italy # of defeats in last 5 games
    if (italyD5 > iranD5) {
        italy -= 1;
    }
    
    if (italyD5 > australiaD5) {
        italy -= 1;
    }

    if (italyD5 > portugalD5) {
        italy -= 1;
    }

    //italy factor of unexpectancy
    if (fitaly > firan) {
        italy += 4;
    }
    
    if (fitaly > faustralia) {
        italy += 4;
    }

    if (fitaly > fportugal) {
        italy += 4;
    }

    //iran factor of unexpectancy
    if (firan > fitaly) {
        iran += 4;
    }
    
    if (firan > faustralia) {
        iran += 4;
    }

    if (firan > fportugal) {
        iran += 4;
    }

    //australia factor of unexpectancy
    if (faustralia > fitaly) {
        australia += 4;
    }
    
    if (faustralia > firan) {
        australia += 4;
    }

    if (faustralia > fportugal) {
        australia += 4;
    }

    //portugal factor of unexpectancy
    if (fportugal > fitaly) {
        portugal += 4;
    }
    
    if (fportugal > firan) {
        portugal += 4;
    }

    if (fportugal > faustralia) {
        portugal += 4;
    }

    //portugal factor of unexpectancy


    
    //1st place results
    if (italy > portugal && italy > australia && italy > iran) {
        cout << "Italy is the winner of Group A" << endl;
        Q1groupA = italy;
        Q1groupAattack = italyattack;
        Q1groupAmidfield = italymidfield;
        Q1groupAdeffence = italydeffence;
        Q1groupAf = fitaly;
        Q1groupAcost = italycost;
        Q1groupApop = italypop;
        Q1groupA5 = italy5;
        Q1groupAC5 = italyC5;
        Q1groupAV5 = italyV5;
        Q1groupAD5 = italyD5;
        FQ1groupA = "Italy";
    }

    else if (portugal > italy && portugal > australia && portugal > iran) {
        cout << "Portugal is the winner of Group A" << endl;
        Q1groupA = portugal;
        Q1groupAattack = portugalattack;
        Q1groupAmidfield = portugalmidfield;
        Q1groupAdeffence = portugaldeffence;
        Q1groupAf = fportugal;
        Q1groupAcost = portugalcost;
        Q1groupApop = portugalpop;
        Q1groupA5 = portugal5;
        Q1groupAC5 = portugalC5;
        Q1groupAV5 = portugalV5;
        Q1groupAD5 = portugalD5;
        FQ1groupA = "Portugal";
    }

    else if (australia > italy && australia > portugal && australia > iran) {
        cout << "Australia is the winner of Group A" << endl;
        Q1groupA = australia;
        Q1groupAattack = australiaattack;
        Q1groupAmidfield = australiamidfield;
        Q1groupAdeffence = australiadeffence;
        Q1groupAf = faustralia;
        Q1groupAcost = australiacost;
        Q1groupApop = australiapop;
        Q1groupA5 = australia5;
        Q1groupAC5 = australiaC5;
        Q1groupAV5 = australiaV5;
        Q1groupAD5 = australiaD5;
        FQ1groupA = "Australia";
    }

    else if (iran > italy && iran > portugal && iran > australia) {
        cout << "Iran is the winner of Group A" << endl;
        Q1groupA = iran;
        Q1groupAattack = iranattack;
        Q1groupAmidfield = iranmidfield;
        Q1groupAdeffence = irandeffence;
        Q1groupAf = firan;
        Q1groupAcost = irancost;
        Q1groupApop = iranpop;
        Q1groupA5 = iran5;
        Q1groupAC5 = iranC5;
        Q1groupAV5 = iranV5;
        Q1groupAD5 = iranD5;
        FQ1groupA = "Iran";
    }

    else {}

    //2nd place results
   
    //Italy
    if (italy > portugal && italy > australia && italy < iran) {
        cout << "Italy is the second of Group A" << endl;
        Q2groupA = italy;
        Q2groupAattack = italyattack;
        Q2groupAmidfield = italymidfield;
        Q2groupAdeffence = italydeffence;
        Q2groupAf = fitaly;
        Q2groupAcost = italycost;
        Q2groupApop = italypop;
        Q2groupA5 = italy5;
        Q2groupAC5 = italyC5;
        Q2groupAV5 = italyV5;
        Q2groupAD5 = italyD5;
        FQ2groupA = "Italy";
    }

    else if (italy > portugal && italy < australia && italy > iran) {
        cout << "Italy is the second of Group A" << endl;
        Q2groupA = italy;
        Q2groupAattack = italyattack;
        Q2groupAmidfield = italymidfield;
        Q2groupAdeffence = italydeffence;
        Q2groupAf = fitaly;
        Q2groupAcost = italycost;
        Q2groupApop = italypop;
        Q2groupA5 = italy5;
        Q2groupAC5 = italyC5;
        Q2groupAV5 = italyV5;
        Q2groupAD5 = italyD5;
        FQ2groupA = "Italy";
    }

    else if (italy < portugal && italy > australia && italy > iran) {
        cout << "Italy is the second of Group A" << endl;
        Q2groupA = italy;
        Q2groupAattack = italyattack;
        Q2groupAmidfield = italymidfield;
        Q2groupAdeffence = italydeffence;
        Q2groupAf = fitaly;
        Q2groupAcost = italycost;
        Q2groupApop = italypop;
        Q2groupA5 = italy5;
        Q2groupAC5 = italyC5;
        Q2groupAV5 = italyV5;
        Q2groupAD5 = italyD5;
        FQ2groupA = "Italy";
    }

    else {}

    //Portugal
    if (portugal > italy && portugal > australia && portugal < iran) {
        cout << "Portugal is the second of Group A" << endl;
        Q2groupA = portugal;
        Q2groupAattack = portugalattack;
        Q2groupAmidfield = portugalmidfield;
        Q2groupAdeffence = portugaldeffence;
        Q1groupAf = fportugal;
        Q1groupAcost = portugalcost;
        Q1groupApop = portugalpop;
        Q1groupA5 = portugal5;
        Q1groupAC5 = portugalC5;
        Q1groupAV5 = portugalV5;
        Q1groupAD5 = portugalD5;
        FQ2groupA = "Portugal";
    }

    else if (portugal > italy && portugal < australia && portugal > iran) {
        cout << "Portugal is the second of Group A" << endl;
        Q2groupA = portugal;
        Q2groupAattack = portugalattack;
        Q2groupAmidfield = portugalmidfield;
        Q2groupAdeffence = portugaldeffence;
        Q1groupAf = fportugal;
        Q1groupAcost = portugalcost;
        Q1groupApop = portugalpop;
        Q1groupA5 = portugal5;
        Q1groupAC5 = portugalC5;
        Q1groupAV5 = portugalV5;
        Q1groupAD5 = portugalD5;
        FQ2groupA = "Portugal";
    }

    else if (portugal < italy && portugal > australia && portugal > iran) {
        cout << "Portugal is the second of Group A" << endl;
        Q2groupA = portugal;
        Q2groupAattack = portugalattack;
        Q2groupAmidfield = portugalmidfield;
        Q2groupAdeffence = portugaldeffence;
        Q1groupAf = fportugal;
        Q1groupAcost = portugalcost;
        Q1groupApop = portugalpop;
        Q1groupA5 = portugal5;
        Q1groupAC5 = portugalC5;
        Q1groupAV5 = portugalV5;
        Q1groupAD5 = portugalD5;
        FQ2groupA = "Portugal";
    }

    else {}

    //Australia
    if (australia > italy && australia > portugal && australia < iran) {
        cout << "Australia is the second of Group A" << endl;
        Q2groupA = australia;
        Q2groupAattack = australiaattack;
        Q2groupAmidfield = australiamidfield;
        Q2groupAdeffence = australiadeffence;
        Q1groupAf = faustralia;
        Q1groupAcost = australiacost;
        Q1groupApop = australiapop;
        Q1groupA5 = australia5;
        Q1groupAC5 = australiaC5;
        Q1groupAV5 = australiaV5;
        Q1groupAD5 = australiaD5;
        FQ2groupA = "Australia";
    }

    else if (australia > italy && australia < portugal && australia > iran) {
        cout << "Australia is the second of Group A" << endl;
        Q2groupA = australia;
        Q2groupAattack = australiaattack;
        Q2groupAmidfield = australiamidfield;
        Q2groupAdeffence = australiadeffence;
        Q1groupAf = faustralia;
        Q1groupAcost = australiacost;
        Q1groupApop = australiapop;
        Q1groupA5 = australia5;
        Q1groupAC5 = australiaC5;
        Q1groupAV5 = australiaV5;
        Q1groupAD5 = australiaD5;
        FQ2groupA = "Australia";
    }

    else if (australia < italy && australia > portugal && australia > iran) {
        cout << "Australia is the second of Group A" << endl;
        Q2groupA = australia;
        Q2groupAattack = australiaattack;
        Q2groupAmidfield = australiamidfield;
        Q2groupAdeffence = australiadeffence;
        Q1groupAf = faustralia;
        Q1groupAcost = australiacost;
        Q1groupApop = australiapop;
        Q1groupA5 = australia5;
        Q1groupAC5 = australiaC5;
        Q1groupAV5 = australiaV5;
        Q1groupAD5 = australiaD5;
        FQ2groupA = "Australia";
    }

    else {}

    //Iran
    if (iran > italy && iran > portugal && iran < australia) {
        cout << "Iran is the second of Group A" << endl;
        Q2groupA = iran;
        Q2groupAattack = iranattack;
        Q2groupAmidfield = iranmidfield;
        Q2groupAdeffence = irandeffence;
        Q1groupAf = firan;
        Q1groupAcost = irancost;
        Q1groupApop = iranpop;
        Q1groupA5 = iran5;
        Q1groupAC5 = iranC5;
        Q1groupAV5 = iranV5;
        Q1groupAD5 = iranD5;
        FQ2groupA = "Iran";
    }

    else if (iran > italy && iran < portugal && iran > australia) {
        cout << "Iran is the second of Group A" << endl;
        Q2groupA = iran;
        Q2groupAattack = iranattack;
        Q2groupAmidfield = iranmidfield;
        Q2groupAdeffence = irandeffence;
        Q1groupAf = firan;
        Q1groupAcost = irancost;
        Q1groupApop = iranpop;
        Q1groupA5 = iran5;
        Q1groupAC5 = iranC5;
        Q1groupAV5 = iranV5;
        Q1groupAD5 = iranD5;
        FQ2groupA = "Iran";
    }

    else if (iran < italy && iran > portugal && iran > australia) {
        cout << "Iran is the second of Group A" << endl;
        Q2groupA = iran;
        Q2groupAattack = iranattack;
        Q2groupAmidfield = iranmidfield;
        Q2groupAdeffence = irandeffence;
        Q1groupAf = firan;
        Q1groupAcost = irancost;
        Q1groupApop = iranpop;
        Q1groupA5 = iran5;
        Q1groupAC5 = iranC5;
        Q1groupAV5 = iranV5;
        Q1groupAD5 = iranD5;
        FQ2groupA = "Iran";
    }

    else {}
    
    //Qualification matches
    
    //Qualified teams' attack, midfield, deffence difference
    
    //Game one's comparison
    //Attack
    if (Q1groupAattack > Q2groupBattack) {
        Q1groupA += 1;
    }

    else if (Q1groupAattack < Q2groupBattack) {
        Q2groupB += 1;
    }

    //midfield
    if (Q1groupAmidfield > Q2groupBmidfield) {
        Q1groupA += 1;
    }

    else if (Q1groupAmidfield < Q2groupBmidfield) {
        Q2groupB += 1;
    }

    //deffence
    if (Q1groupAdeffence > Q2groupBdeffence) {
        Q1groupA += 1;
    }

    else if (Q1groupAdeffence < Q2groupBdeffence) {
        Q2groupB += 1;
    }
    
    
    //factor of unexpectancy
    if (Q1groupAf > Q2groupBf) {
        Q1groupA += 1;
    }

    else if (Q1groupAf < Q2groupBf) {
        Q2groupB += 1;
    }
    //cost of teams
    if (Q1groupAcost > Q2groupBcost) {
        Q1groupA += 1;
    }

    else if (Q1groupAcost < Q2groupBcost) {
        Q2groupB += 1;
    }
    //popuplation
    if (Q1groupApop > Q2groupBpop) {
        Q1groupA += 1;
    }

    else if (Q1groupApop < Q2groupBpop) {
        Q2groupB += 1;
    }
    
    //# of goals score in last 5 games
    if (Q1groupA5 > Q2groupB5) {
        Q1groupA += 1;
    }

    else if (Q1groupA5 < Q2groupB5) {
        Q2groupB += 1;
    }

    //# of goals conceded in last 5 games
    if (Q1groupAC5 > Q2groupBC5) {
        Q1groupA += 1;
    }

    else if (Q1groupAC5 < Q2groupBC5) {
        Q2groupB += 1;
    }

    //# of victories in last 5 games
    if (Q1groupAV5 > Q2groupBV5) {
        Q1groupA += 1;
    }

    else if (Q1groupAV5 < Q2groupBV5) {
        Q2groupB += 1;
    }
    //# of defeats in last 5 games
    if (Q1groupAD5 > Q2groupBD5) {
        Q1groupA += 1;
    }

    else if (Q1groupAD5 < Q2groupBD5) {
        Q2groupB += 1;
    }
    
    
    //Game two's comparison
    //Attack
    if (Q1groupBattack > Q2groupAattack) {
        Q1groupB += 1;
    }

    else if (Q1groupBattack < Q2groupAattack) {
        Q2groupA += 1;
    }

    //midfield
    if (Q1groupBmidfield > Q2groupAmidfield) {
        Q1groupB += 1;
    }

    else if (Q1groupBmidfield < Q2groupAmidfield) {
        Q2groupA += 1;
    }

    //deffence
    if (Q1groupBdeffence > Q2groupAdeffence) {
        Q1groupB += 1;
    }

    else if (Q1groupBdeffence < Q2groupAdeffence) {
        Q2groupA += 1;
    }
    int Q1groupAf, Q1groupBf, Q1groupCf, Q1groupDf, Q1groupEf, Q1groupFf, Q1groupGf, Q1groupHf, Q2groupAf, Q2groupBf, Q2groupCf, Q2groupDf, Q2groupEf, Q2groupFf, Q2groupGf, Q2groupHf;
    
    //factor of unexpectancy
    if (Q1groupBf > Q2groupAf) {
        Q1groupB += 1;
    }

    else if (Q1groupBf < Q2groupAf) {
        Q2groupA += 1;
    }
    //cost of teams
    if (Q1groupBcost > Q2groupAcost) {
        Q1groupB += 1;
    }

    else if (Q1groupBcost < Q2groupAcost) {
        Q2groupA += 1;
    }
    //popuplation
    if (Q1groupBpop > Q2groupApop) {
        Q1groupB += 1;
    }

    else if (Q1groupBpop < Q2groupApop) {
        Q2groupA += 1;
    }
    
    //# of goals score in last 5 games
    if (Q1groupB5 > Q2groupA5) {
        Q1groupB += 1;
    }

    else if (Q1groupB5 < Q2groupA5) {
        Q2groupA += 1;
    }
    //# of goals conceded in last 5 games
    if (Q1groupBC5 > Q2groupAC5) {
        Q1groupB += 1;
    }

    else if (Q1groupBC5 < Q2groupAC5) {
        Q2groupA += 1;
    }
    //# of victories in last 5 games
    if (Q1groupBV5 > Q2groupAV5) {
        Q1groupB += 1;
    }

    else if (Q1groupBV5 < Q2groupAV5) {
        Q2groupA += 1;
    }
    //# of defeats in last 5 games
    if (Q1groupBD5 > Q2groupAD5) {
        Q1groupB += 1;
    }

    else if (Q1groupBD5 < Q2groupAD5) {
        Q2groupA += 1;
    }

    
    
    //Game three's comparison
    //Attack
    if (Q1groupCattack > Q2groupDattack) {
        Q1groupC += 1;
    }

    else if (Q1groupCattack < Q2groupDattack) {
        Q2groupD += 1;
    }

    //midfield
    if (Q1groupCmidfield > Q2groupDmidfield) {
        Q1groupC += 1;
    }

    else if (Q1groupCmidfield < Q2groupDmidfield) {
        Q2groupD += 1;
    }

    //deffence
    if (Q1groupCdeffence > Q2groupDdeffence) {
        Q1groupC += 1;
    }

    else if (Q1groupCdeffence < Q2groupDdeffence) {
        Q2groupD += 1;
    }
    
    
    //factor of unexpectancy
    if (Q1groupCf > Q2groupDf) {
        Q1groupC += 1;
    }

    else if (Q1groupCf < Q2groupDf) {
        Q2groupD += 1;
    }
    //cost of teams
    if (Q1groupCcost > Q2groupDcost) {
        Q1groupC += 1;
    }

    else if (Q1groupCcost < Q2groupDcost) {
        Q2groupD += 1;
    }
    //popuplation
    if (Q1groupCpop > Q2groupDpop) {
        Q1groupC += 1;
    }

    else if (Q1groupCpop < Q2groupDpop) {
        Q2groupD += 1;
    }
    
    //# of goals score in last 5 games
    if (Q1groupC5 > Q2groupD5) {
        Q1groupC += 1;
    }

    else if (Q1groupC5 < Q2groupD5) {
        Q2groupD += 1;
    }

    //# of goals conceded in last 5 games
    if (Q1groupCC5 > Q2groupDC5) {
        Q1groupC += 1;
    }

    else if (Q1groupCC5 < Q2groupDC5) {
        Q2groupD += 1;
    }

    //# of victories in last 5 games
    if (Q1groupCV5 > Q2groupDV5) {
        Q1groupC += 1;
    }

    else if (Q1groupCV5 < Q2groupDV5) {
        Q2groupD += 1;
    }
    //# of defeats in last 5 games
    if (Q1groupCD5 > Q2groupDD5) {
        Q1groupC += 1;
    }

    else if (Q1groupCD5 < Q2groupDD5) {
        Q2groupD += 1;
    }


    //Game four's comparison
    //Attack
    if (Q2groupCattack > Q1groupDattack) {
        Q2groupC += 1;
    }

    else if (Q2groupCattack < Q1groupDattack) {
        Q1groupD += 1;
    }

    //midfield
    if (Q2groupCmidfield > Q1groupDmidfield) {
        Q2groupC += 1;
    }

    else if (Q2groupCmidfield < Q1groupDmidfield) {
        Q1groupD += 1;
    }

    //deffence
    if (Q2groupCdeffence > Q1groupDdeffence) {
        Q2groupC += 1;
    }

    else if (Q2groupCdeffence < Q1groupDdeffence) {
        Q1groupD += 1;
    }
    
    
    //factor of unexpectancy
    if (Q2groupCf > Q1groupDf) {
        Q2groupC += 1;
    }

    else if (Q2groupCf < Q1groupDf) {
        Q1groupD += 1;
    }
    //cost of teams
    if (Q2groupCcost > Q1groupDcost) {
        Q2groupC += 1;
    }

    else if (Q2groupCcost < Q1groupDcost) {
        Q1groupD += 1;
    }
    //popuplation
    if (Q2groupCpop > Q1groupDpop) {
        Q2groupC += 1;
    }

    else if (Q2groupCpop < Q1groupDpop) {
        Q1groupD += 1;
    }
    
    //# of goals score in last 5 games
    if (Q2groupC5 > Q1groupD5) {
        Q2groupC += 1;
    }

    else if (Q2groupC5 < Q1groupD5) {
        Q1groupD += 1;
    }

    //# of goals conceded in last 5 games
    if (Q2groupCC5 > Q1groupDC5) {
        Q2groupC += 1;
    }

    else if (Q2groupCC5 < Q1groupDC5) {
        Q1groupD += 1;
    }

    //# of victories in last 5 games
    if (Q2groupCV5 > Q1groupDV5) {
        Q2groupC += 1;
    }

    else if (Q2groupCV5 < Q1groupDV5) {
        Q1groupD += 1;
    }
    //# of defeats in last 5 games
    if (Q2groupCD5 > Q1groupDD5) {
        Q2groupC += 1;
    }

    else if (Q2groupCD5 < Q1groupDD5) {
        Q1groupD += 1;
    }


    //Game five's comparison
    //Attack
    if (Q1groupEattack > Q2groupFattack) {
        Q1groupE += 1;
    }

    else if (Q1groupEattack < Q2groupFattack) {
        Q2groupF += 1;
    }

    //midfield
    if (Q1groupEmidfield > Q2groupFmidfield) {
        Q1groupE += 1;
    }

    else if (Q1groupEmidfield < Q2groupFmidfield) {
        Q2groupF += 1;
    }

    //deffence
    if (Q1groupEdeffence > Q2groupFdeffence) {
        Q1groupE += 1;
    }

    else if (Q1groupEdeffence < Q2groupFdeffence) {
        Q2groupF += 1;
    }
    
    
    //factor of unexpectancy
    if (Q1groupEf > Q2groupFf) {
        Q1groupE += 1;
    }

    else if (Q1groupEf < Q2groupFf) {
        Q2groupF += 1;
    }
    //cost of teams
    if (Q1groupEcost > Q2groupFcost) {
        Q1groupE += 1;
    }

    else if (Q1groupEcost < Q2groupFcost) {
        Q2groupF += 1;
    }
    //popuplation
    if (Q1groupEpop > Q2groupFpop) {
        Q1groupE += 1;
    }

    else if (Q1groupEpop < Q2groupFpop) {
        Q2groupF += 1;
    }
    
    //# of goals score in last 5 games
    if (Q1groupE5 > Q2groupF5) {
        Q1groupE += 1;
    }

    else if (Q1groupE5 < Q2groupF5) {
        Q2groupF += 1;
    }

    //# of goals conceded in last 5 games
    if (Q1groupEC5 > Q2groupFC5) {
        Q1groupE += 1;
    }

    else if (Q1groupEC5 < Q2groupFC5) {
        Q2groupF += 1;
    }

    //# of victories in last 5 games
    if (Q1groupEV5 > Q2groupFV5) {
        Q1groupE += 1;
    }

    else if (Q1groupEV5 < Q2groupFV5) {
        Q2groupF += 1;
    }
    //# of defeats in last 5 games
    if (Q1groupED5 > Q2groupFD5) {
        Q1groupE += 1;
    }

    else if (Q1groupED5 < Q2groupFD5) {
        Q2groupF += 1;
    }


    //Game six's comparison
    //Attack
    if (Q2groupEattack > Q1groupFattack) {
        Q2groupE += 1;
    }

    else if (Q2groupEattack < Q1groupFattack) {
        Q1groupF += 1;
    }

    //midfield
    if (Q2groupEmidfield > Q1groupFmidfield) {
        Q2groupE += 1;
    }

    else if (Q2groupEmidfield < Q1groupFmidfield) {
        Q1groupF += 1;
    }

    //deffence
    if (Q2groupEdeffence > Q1groupFdeffence) {
        Q2groupE += 1;
    }

    else if (Q2groupEdeffence < Q1groupFdeffence) {
        Q1groupF += 1;
    }
    
    
    //factor of unexpectancy
    if (Q2groupEf > Q1groupFf) {
        Q2groupE += 1;
    }

    else if (Q2groupEf < Q1groupFf) {
        Q1groupF += 1;
    }
    //cost of teams
    if (Q2groupEcost > Q1groupFcost) {
        Q2groupE += 1;
    }

    else if (Q2groupEcost < Q1groupFcost) {
        Q1groupF += 1;
    }
    //popuplation
    if (Q2groupEpop > Q1groupFpop) {
        Q2groupE += 1;
    }

    else if (Q2groupEpop < Q1groupFpop) {
        Q2groupF += 1;
    }
    
    //# of goals score in last 5 games
    if (Q2groupE5 > Q1groupF5) {
        Q2groupE += 1;
    }

    else if (Q2groupE5 < Q1groupF5) {
        Q1groupF += 1;
    }

    //# of goals conceded in last 5 games
    if (Q2groupEC5 > Q1groupFC5) {
        Q2groupE += 1;
    }

    else if (Q2groupEC5 < Q1groupFC5) {
        Q1groupF += 1;
    }

    //# of victories in last 5 games
    if (Q2groupEV5 > Q1groupFV5) {
        Q2groupE += 1;
    }

    else if (Q2groupEV5 < Q1groupFV5) {
        Q1groupF += 1;
    }
    //# of defeats in last 5 games
    if (Q2groupED5 > Q1groupFD5) {
        Q2groupE += 1;
    }

    else if (Q2groupED5 < Q1groupFD5) {
        Q1groupF += 1;
    }


    //Game seven's comparison
    //Attack
    if (Q1groupGattack > Q2groupHattack) {
        Q1groupG += 1;
    }

    else if (Q1groupGattack < Q2groupHattack) {
        Q2groupH += 1;
    }

    //midfield
    if (Q1groupGmidfield > Q2groupHmidfield) {
        Q1groupG += 1;
    }

    else if (Q1groupGmidfield < Q2groupHmidfield) {
        Q2groupH += 1;
    }

    //deffence
    if (Q1groupGdeffence > Q2groupHdeffence) {
        Q1groupG += 1;
    }

    else if (Q1groupGdeffence < Q2groupHdeffence) {
        Q2groupH += 1;
    }
    
    
    //factor of unexpectancy
    if (Q1groupGf > Q2groupHf) {
        Q1groupG += 1;
    }

    else if (Q1groupGf < Q2groupHf) {
        Q2groupH += 1;
    }
    //cost of teams
    if (Q1groupGcost > Q2groupHcost) {
        Q1groupG += 1;
    }

    else if (Q1groupGcost < Q2groupHcost) {
        Q2groupH += 1;
    }
    //popuplation
    if (Q1groupGpop > Q2groupHpop) {
        Q1groupG += 1;
    }

    else if (Q1groupGpop < Q2groupHpop) {
        Q2groupH += 1;
    }
    
    //# of goals score in last 5 games
    if (Q1groupG5 > Q2groupH5) {
        Q1groupG += 1;
    }

    else if (Q1groupG5 < Q2groupH5) {
        Q2groupH += 1;
    }

    //# of goals conceded in last 5 games
    if (Q1groupGC5 > Q2groupHC5) {
        Q1groupG += 1;
    }

    else if (Q1groupGC5 < Q2groupHC5) {
        Q2groupH += 1;
    }

    //# of victories in last 5 games
    if (Q1groupGV5 > Q2groupHV5) {
        Q1groupG += 1;
    }

    else if (Q1groupGV5 < Q2groupHV5) {
        Q2groupH += 1;
    }
    //# of defeats in last 5 games
    if (Q1groupGD5 > Q2groupHD5) {
        Q1groupG += 1;
    }

    else if (Q1groupGD5 < Q2groupHD5) {
        Q2groupH += 1;
    }


    //Game eight's comparison
    //Attack
    if (Q2groupGattack > Q1groupHattack) {
        Q2groupG += 1;
    }

    else if (Q2groupGattack < Q1groupHattack) {
        Q1groupH += 1;
    }

    //midfield
    if (Q2groupGmidfield > Q1groupHmidfield) {
        Q2groupG += 1;
    }

    else if (Q2groupGmidfield < Q1groupHmidfield) {
        Q1groupH += 1;
    }

    //deffence
    if (Q2groupGdeffence > Q1groupHdeffence) {
        Q2groupG += 1;
    }

    else if (Q2groupGdeffence < Q1groupHdeffence) {
        Q1groupH += 1;
    }
    
    
    //factor of unexpectancy
    if (Q2groupGf > Q1groupHf) {
        Q2groupG += 1;
    }

    else if (Q2groupGf < Q1groupHf) {
        Q1groupH += 1;
    }
    //cost of teams
    if (Q2groupGcost > Q1groupHcost) {
        Q2groupG += 1;
    }

    else if (Q2groupGcost < Q1groupHcost) {
        Q1groupH += 1;
    }
    //popuplation
    if (Q2groupGpop > Q1groupHpop) {
        Q2groupG += 1;
    }

    else if (Q2groupGpop < Q1groupHpop) {
        Q1groupH += 1;
    }
    
    //# of goals score in last 5 games
    if (Q2groupG5 > Q1groupH5) {
        Q2groupG += 1;
    }

    else if (Q2groupG5 < Q1groupH5) {
        Q1groupH += 1;
    }

    //# of goals conceded in last 5 games
    if (Q2groupGC5 > Q1groupHC5) {
        Q2groupG += 1;
    }

    else if (Q2groupGC5 < Q1groupHC5) {
        Q1groupH += 1;
    }

    //# of victories in last 5 games
    if (Q2groupGV5 > Q1groupHV5) {
        Q2groupG += 1;
    }

    else if (Q2groupGV5 < Q1groupHV5) {
        Q1groupH += 1;
    }
    //# of defeats in last 5 games
    if (Q2groupGD5 > Q1groupHD5) {
        Q2groupG += 1;
    }

    else if (Q2groupGD5 < Q1groupHD5) {
        Q1groupH += 1;
    }


    cout << endl;
     int QFgame1;
    int QFgame2;
    int QFgame3;
    int QFgame4;
    int QFgame5;
    int QFgame6;
    int QFgame7;
    int QFgame8;
    string FQFgame1;
    string FQFgame2;
    string FQFgame3;
    string FQFgame4;
    string FQFgame5;
    string FQFgame6;
    string FQFgame7;
    string FQFgame8;
    int QFgame1attack, QFgame2attack, QFgame3attack, QFgame4attack, QFgame5attack, QFgame6attack, QFgame7attack, QFgame8attack;
    int QFgame1midfield, QFgame2midfield, QFgame3midfield, QFgame4midfield, QFgame5midfield, QFgame6midfield, QFgame7midfield, QFgame8midfield;
    int QFgame1deffence, QFgame2deffence, QFgame3deffence, QFgame4deffence, QFgame5deffence, QFgame6deffence, QFgame7deffence, QFgame8deffence;
    int QFgame1f, QFgame2f, QFgame3f, QFgame4f, QFgame5f, QFgame6f, QFgame7f, QFgame8f;
    int QFgame1cost, QFgame2cost, QFgame3cost, QFgame4cost, QFgame5cost, QFgame6cost, QFgame7cost, QFgame8cost;
    int QFgame1pop, QFgame2pop, QFgame3pop, QFgame4pop, QFgame5pop, QFgame6pop, QFgame7pop, QFgame8pop;
    int QFgame15, QFgame25, QFgame35, QFgame45, QFgame55, QFgame65, QFgame75, QFgame85;
    int QFgame1C5, QFgame2C5, QFgame3C5, QFgame4C5, QFgame5C5, QFgame6C5, QFgame7C5, QFgame8C5;
    int QFgame1V5, QFgame2V5, QFgame3V5, QFgame4V5, QFgame5V5, QFgame6V5, QFgame7V5, QFgame8V5;
    int QFgame1D5, QFgame2D5, QFgame3D5, QFgame4D5, QFgame5D5, QFgame6D5, QFgame7D5, QFgame8D5;
    
    int Q1groupAattack, Q1groupBattack, Q1groupCattack, Q1groupDattack, Q1groupEattack, Q1groupFattack, Q1groupGattack, Q1groupHattack, Q2groupAattack, Q2groupBattack, Q2groupCattack, Q2groupDattack, Q2groupEattack, Q2groupFattack, Q2groupGattack, Q2groupHattack;
    int Q1groupAmidfield, Q1groupBmidfield, Q1groupCmidfield, Q1groupDmidfield, Q1groupEmidfield, Q1groupFmidfield, Q1groupGmidfield, Q1groupHmidfield, Q2groupAmidfield, Q2groupBmidfield, Q2groupCmidfield, Q2groupDmidfield, Q2groupEmidfield, Q2groupFmidfield, Q2groupGmidfield, Q2groupHmidfield;
    int Q1groupAdeffence, Q1groupBdeffence, Q1groupCdeffence, Q1groupDdeffence, Q1groupEdeffence, Q1groupFdeffence, Q1groupGdeffence, Q1groupHdeffence, Q2groupAdeffence, Q2groupBdeffence, Q2groupCdeffence, Q2groupDdeffence, Q2groupEdeffence, Q2groupFdeffence, Q2groupGdeffence, Q2groupHdeffence;
    int Q1groupAf, Q1groupBf, Q1groupCf, Q1groupDf, Q1groupEf, Q1groupFf, Q1groupGf, Q1groupHf, Q2groupAf, Q2groupBf, Q2groupCf, Q2groupDf, Q2groupEf, Q2groupFf, Q2groupGf, Q2groupHf;
    int Q1groupAcost, Q1groupBcost, Q1groupCcost, Q1groupDcost, Q1groupEcost, Q1groupFcost, Q1groupGcost, Q1groupHcost, Q2groupAcost, Q2groupBcost, Q2groupCcost, Q2groupDcost, Q2groupEcost, Q2groupFcost, Q2groupGcost, Q2groupHcost;
    int Q1groupApop, Q1groupBpop, Q1groupCpop, Q1groupDpop, Q1groupEpop, Q1groupFpop, Q1groupGpop, Q1groupHpop, Q2groupApop, Q2groupBpop, Q2groupCpop, Q2groupDpop, Q2groupEpop, Q2groupFpop, Q2groupGpop, Q2groupHpop;
    int Q1groupA5, Q1groupB5, Q1groupC5, Q1groupD5, Q1groupE5, Q1groupF5, Q1groupG5, Q1groupH5, Q2groupA5, Q2groupB5, Q2groupC5, Q2groupD5, Q2groupE5, Q2groupF5, Q2groupG5, Q2groupH5;
    int Q1groupAC5, Q1groupBC5, Q1groupCC5, Q1groupDC5, Q1groupEC5, Q1groupFC5, Q1groupGC5, Q1groupHC5, Q2groupAC5, Q2groupBC5, Q2groupCC5, Q2groupDC5, Q2groupEC5, Q2groupFC5, Q2groupGC5, Q2groupHC5;
    int Q1groupAV5, Q1groupBV5, Q1groupCV5, Q1groupDV5, Q1groupEV5, Q1groupFV5, Q1groupGV5, Q1groupHV5, Q2groupAV5, Q2groupBV5, Q2groupCV5, Q2groupDV5, Q2groupEV5, Q2groupFV5, Q2groupGV5, Q2groupHV5;
    int Q1groupAD5, Q1groupBD5, Q1groupCD5, Q1groupDD5, Q1groupED5, Q1groupFD5, Q1groupGD5, Q1groupHD5, Q2groupAD5, Q2groupBD5, Q2groupCD5, Q2groupDD5, Q2groupED5, Q2groupFD5, Q2groupGD5, Q2groupHD5;
    //Round 1 match results
    //game 1
    if (Q1groupA > Q2groupB) {
        cout << FQ1groupA <<" won "<< FQ2groupB << " in round 1" << endl;
        QFgame1 = Q1groupA;
        QFgame1attack = Q1groupAattack;
        QFgame1midfield = Q1groupAmidfield;
        QFgame1deffence = Q1groupAdeffence;
        QFgame1f =
        QFgame1cost = 
        QFgame1pop =
        QFgame15 =
        QFgame1C5 =

        
        FQFgame1 = FQ1groupA;
        
    }

    if (Q1groupA < Q2groupB) {
        cout << FQ2groupB <<" won "<< FQ1groupA << " in round 1" << endl;
        QFgame1 = Q2groupB;
        QFgame1attack = Q2groupBattack;
        QFgame1midfield = Q2groupBmidfield;
        QFgame1deffence = Q2groupBdeffence;
        
        FQFgame1 = FQ2groupB;
        
    }

    //game 2
    if (Q2groupA > Q1groupB) {
        cout << FQ2groupA <<" won "<< FQ1groupB << " in round 1" << endl;
        QFgame2 = Q2groupA;
        QFgame2attack = Q2groupAattack;
        QFgame2midfield = Q2groupAmidfield;
        QFgame2deffence = Q2groupAdeffence;
       
        FQFgame2 = FQ2groupA;
        
    }

    if (Q2groupA < Q1groupB) {
        cout << FQ1groupB <<" won "<< FQ2groupA << " in round 1" << endl;
        QFgame2 = Q1groupB;
        QFgame2attack = Q1groupBattack;
        QFgame2midfield = Q1groupBmidfield;
        QFgame2deffence = Q1groupBdeffence;
        
        FQFgame2 = FQ1groupB;
        
    }

    //game 3

    //game 4

    //game 5

    //game 6

    //game 7

    //game 8


    
    //Comparison of quarter-finals teams' attack
    //Game one's comparison
    //Attack

    //midfield

    //deffence

    //factor of unexpectancy

    //cost of teams

    //popuplation

    //# of goals score in last 5 games

    //# of goals conceded in last 5 games

    //# of victories in last 5 games

    //# of defeats in last 5 games


    //Game two's comparison
    //Attack

    //midfield

    //deffence

    //factor of unexpectancy

    //cost of teams

    //popuplation

    //# of goals score in last 5 games

    //# of goals conceded in last 5 games

    //# of victories in last 5 games

    //# of defeats in last 5 games


    //Game three's comparison
    //Attack

    //midfield

    //deffence

    //factor of unexpectancy

    //cost of teams

    //popuplation

    //# of goals score in last 5 games

    //# of goals conceded in last 5 games

    //# of victories in last 5 games

    //# of defeats in last 5 games


    //Game four's comparison
    //Attack

    //midfield

    //deffence

    //factor of unexpectancy

    //cost of teams

    //popuplation

    //# of goals score in last 5 games

    //# of goals conceded in last 5 games

    //# of victories in last 5 games

    //# of defeats in last 5 games


    //Quarter-finals match results
    //game 1

    //game 2

    //game 3

    //game 4

    
    
    //Comparison of semi-finals teams' attack
    //Game one's comparison
    //Attack

    //midfield

    //deffence

    //factor of unexpectancy

    //cost of teams

    //popuplation

    //# of goals score in last 5 games

    //# of goals conceded in last 5 games

    //# of victories in last 5 games

    //# of defeats in last 5 games


    //Game two's comparison
    //Attack

    //midfield

    //deffence

    //factor of unexpectancy

    //cost of teams

    //popuplation

    //# of goals score in last 5 games

    //# of goals conceded in last 5 games

    //# of victories in last 5 games

    //# of defeats in last 5 games


    //Semi-finals match results
    //game 1

    //game 2

    //Comparison of finals teams' attack
    if (R1game1Fattack > R1game2Fattack) {
        R1game1F += 1;
    }

    else if (R1game1Fattack < R1game2Fattack) {
        R1game2F += 1;
    }

    //Comparison of finals teams' midfield
    if (R1game1Fmidfield > R1game2Fmidfield) {
        R1game1F += 1;
    }

    else if (R1game1Fmidfield < R1game2Fmidfield) {
        R1game2F += 1;
    }

    //Comparison of finals teams' defence
    if (R1game1Fdeffence > R1game2Fdeffence) {
        R1game1F += 1;
    }

    else if (R1game1Fdeffence < R1game2Fdeffence) {
        R1game2F += 1;
    }

    //factor of unexpectancy

    //cost of teams

    //popuplation

    //# of goals score in last 5 games

    //# of goals conceded in last 5 games

    //# of victories in last 5 games

    //# of defeats in last 5 games


    //Comparison of third place game's teams' attack
    if (R1game1Tattack > R1game2Tattack) {
        R1game1T += 1;
    }

    else if (R1game1Tattack < R1game2Tattack) {
        R1game2T += 1;
    }

    //Comparison of third place game's teams' midfield
    if (R1game1Tmidfield > R1game2Tmidfield) {
        R1game1T += 1;
    }

    else if (R1game1Tmidfield < R1game2Tmidfield) {
        R1game2T += 1;
    }

    //Comparison of third place game's teams' defence
    if (R1game1Tdeffence > R1game2Tdeffence) {
        R1game1T += 1;
    }

    else if (R1game1Tdeffence < R1game2Tdeffence) {
        R1game2T += 1;
    }

    //factor of unexpectancy

    //cost of teams

    //popuplation

    //# of goals score in last 5 games

    //# of goals conceded in last 5 games

    //# of victories in last 5 games

    //# of defeats in last 5 games


    cout << endl;

    //Third Place
    if (R1game1T > R1game2T) {
       cout << FR1game1T << " are the third place winners";
    }

    else if (R1game1T < R1game2T) {
       cout << FR1game2T << " are the third place winners";
    }

    cout << endl;

    //Finals
    if (R1game1F > R1game2F) {
       cout << FR1game1F << " are the World Cup Champions!!!!!!!!!!!!!!!!!!!!!!!!!!!";
    }

    else if (R1game1F < R1game2F) {
       cout << FR1game2F << " are the World Cup Champions!!!!!!!!!!!!!!!!!!!!!!!!!!!";
    }
    
    





















/*//Round 1 match results
    //game 1
    if (Q1groupA > Q2groupB) {
        cout << FQ1groupA <<" won "<< FQ2groupB << " in round 1" << endl;
        R1game1F = Q1groupA;
        R1game1Fattack = Q1groupAattack;
        R1game1Fmidfield = Q1groupAmidfield;
        R1game1Fdeffence = Q1groupAdeffence;
        R1game1T = Q2groupB;
        R1game1Tattack = Q2groupBattack;
        R1game1Tmidfield = Q2groupBmidfield;
        R1game1Tdeffence = Q2groupBdeffence;
        FR1game1F = FQ1groupA;
        FR1game1T = FQ2groupB;
    }

    if (Q1groupA < Q2groupB) {
        cout << FQ2groupB <<" won "<< FQ1groupA << " in round 1" << endl;
        R1game1F = Q2groupB;
        R1game1Fattack = Q2groupBattack;
        R1game1Fmidfield = Q2groupBmidfield;
        R1game1Fdeffence = Q2groupBdeffence;
        R1game1T = Q1groupA;
        R1game1Tattack = Q1groupAattack;
        R1game1Tmidfield = Q1groupAmidfield;
        R1game1Tdeffence = Q1groupAdeffence;
        FR1game1F = FQ2groupB;
        FR1game1T = FQ1groupA;
    }

    //game 2
    if (Q2groupA > Q1groupB) {
        cout << FQ2groupA <<" won "<< FQ1groupB << " in round 1" << endl;
        R1game2F = Q2groupA;
        R1game2Fattack = Q2groupAattack;
        R1game2Fmidfield = Q2groupAmidfield;
        R1game2Fdeffence = Q2groupAdeffence;
        R1game2T = Q1groupB;
        R1game2Tattack = Q1groupBattack;
        R1game2Tmidfield = Q1groupBmidfield;
        R1game2Tdeffence = Q1groupBdeffence;
        FR1game2F = FQ2groupA;
        FR1game2T = FQ1groupB;
    }

    if (Q2groupA < Q1groupB) {
        cout << FQ1groupB <<" won "<< FQ2groupA << " in round 1" << endl;
        R1game2F = Q1groupB;
        R1game2Fattack = Q1groupBattack;
        R1game2Fmidfield = Q1groupBmidfield;
        R1game2Fdeffence = Q1groupBdeffence;
        R1game2T = Q2groupA;
        R1game2Tattack = Q2groupAattack;
        R1game2Tmidfield = Q2groupAmidfield;
        R1game2Tdeffence = Q2groupAdeffence;
        FR1game2F = FQ1groupB;
        FR1game2T = FQ2groupA;
    }
    
    //Third Place
    if (R1game1T > R1game2T) {
       cout << FR1game1T << " are the third place winners";
    }

    else if (R1game1T < R1game2T) {
       cout << FR1game2T << " are the third place winners";
    }

    cout << endl;

    //Finals
    if (R1game1F > R1game2F) {
       cout << FR1game1F << " are the World Cup Champions!!!!!!!!!!!!!!!!!!!!!!!!!!!";
    }

    else if (R1game1F < R1game2F) {
       cout << FR1game2F << " are the World Cup Champions!!!!!!!!!!!!!!!!!!!!!!!!!!!";
    }*/

}
