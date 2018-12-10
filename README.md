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

    //Qualified teams
    
    //Qulified in 1st place from group A
    int Q1groupA;
    string FQ1groupA;


    //Qulified in 1st place from group B
    int Q1groupB;
    string FQ1groupB;

    //Qualified in 2nd place from group A
    int Q2groupA;
    string FQ2groupA;

    //Qualified in 2nd place from group B
    int Q2groupB;
    string FQ2groupB;
    
    //Qualified teams' attack, midfield, deffence of round 1
    int Q1groupAattack, Q1groupBattack, Q2groupAattack, Q2groupBattack;
    int Q1groupAmidfield, Q1groupBmidfield, Q2groupAmidfield, Q2groupBmidfield;
    int Q1groupAdeffence, Q1groupBdeffence, Q2groupAdeffence, Q2groupBdeffence;
    
    //Finals teams' attack, midfield, deffence of round 1
    int R1game1Fattack, R1game2Fattack;
    int R1game1Fmidfield, R1game2Fmidfield;
    int R1game1Fdeffence, R1game2Fdeffence;

    //Match for third place teams' attack, midfield, deffence of round 1
    int R1game1Tattack, R1game2Tattack;
    int R1game1Tmidfield, R1game2Tmidfield;
    int R1game1Tdeffence, R1game2Tdeffence;

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

    //# of goals scored in last 15 games
    int italy15 = 9;
    int portugal15 = 22;
    int australia15 = 23;
    int iran15 = 18;

    //# of goals conceded in last 15 games
    int italyC15 = 13;
    int portugalC15 = 17;
    int australiaC15 = 17;
    int iranC15 = 10;

    //# of victories in last 15 games
    int italyV15 = 4;
    int portugalV15 = 6;
    int australiaV15 = 6;
    int iranV15 = 8;

    //# of defeats in last 15 games
    int italyD15 = 4;
    int portugalD15 = 2;
    int australiaD15 = 4;
    int iranD15 = 3;

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
    
    //# of goals scored in last 15 games
    int croatia15 = 24;
    int belgium15 = 37;
    int denmark15 = 17;
    int columbia15 = 21;

    //# of goals conceded in last 15 games
    int croatiaC15 = 15;
    int belgiumC15 = 14;
    int denmarkC15 = 7;
    int columbiaC15 = 14;

    //# of victories in last 15 games
    int croatiaV15 = 9;
    int belgiumV15 = 12;
    int denmarkV15 = 7;
    int columbiaV15 = 8;

    //# of defeats in last 15 games
    int croatiaD15 = 4;
    int belgiumD15 = 2;
    int denmarkD15 = 2;
    int columbiaD15 = 4;

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

    //croatia # of goals scored in last 15 games
    if (croatia15 > belgium15) {
        croatia += 1;
    }
    
    if (croatia15 > denmark15) {
        croatia += 1;
    }

    if (croatia15 > columbia15) {
        croatia += 1;
    }

    //belgium # of goals scored in last 15 games
    if (belgium15 > croatia15) {
        belgium += 1;
    }
    
    if (belgium15 > denmark15) {
        belgium += 1;
    }

    if (belgium15 > columbia15) {
        belgium += 1;
    }

    //denmark # of goals scored in last 15 games
    if (denmark15 > croatia15) {
        denmark += 1;
    }
    
    if (denmark15 > belgium15) {
        denmark += 1;
    }

    if (denmark15 > columbia15) {
        denmark += 1;
    }

    //columbia # of goals scored in last 15 games
    if (columbia15 > croatia15) {
        columbia += 1;
    }
    
    if (columbia15 > belgium15) {
        columbia += 1;
    }

    if (columbia15 > denmark15) {
        columbia += 1;
    }

    //columbia # of goals conceded in last 15 games
    if (columbiaC15 > denmarkC15) {
        columbia -= 1;
    }
    
    if (columbiaC15 > belgiumC15) {
        columbia -= 1;
    }

    if (columbiaC15 > croatiaC15) {
        columbia -= 1;
    }

    //denmark # of goals conceded in last 15 games
    if (denmarkC15 > columbiaC15) {
        denmark -= 1;
    }
    
    if (denmarkC15 > belgiumC15) {
        denmark -= 1;
    }

    if (denmarkC15 > croatiaC15) {
        denmark -= 1;
    }

    //belgium # of goals conceded in last 15 games
    if (belgiumC15 > columbiaC15) {
        belgium -= 1;
    }
    
    if (belgiumC15 > denmarkC15) {
        belgium -= 1;
    }

    if (belgiumC15 > croatiaC15) {
        belgium -= 1;
    }

    //croatia # of goals conceded in last 15 games
    if (croatiaC15 > columbiaC15) {
        croatia -= 1;
    }
    
    if (croatiaC15 > denmarkC15) {
        croatia -= 1;
    }

    if (croatiaC15 > belgiumC15) {
        croatia -= 1;
    }

    //croatia # of victories in last 15 games
    if (croatiaV15 > belgiumV15) {
        croatia += 1;
    }
    
    if (croatiaV15 > denmarkV15) {
        croatia += 1;
    }

    if (croatiaV15 > columbiaV15) {
        croatia += 1;
    }

    //belgium # of victories in last 15 games
    if (belgiumV15 > croatiaV15) {
        belgium += 1;
    }
    
    if (belgiumV15 > denmarkV15) {
        belgium += 1;
    }

    if (belgiumV15 > columbiaV15) {
        belgium += 1;
    }

    //denmark # of victories in last 15 games
    if (denmarkV15 > croatiaV15) {
        denmark += 1;
    }
    
    if (denmarkV15 > belgiumV15) {
        denmark += 1;
    }

    if (denmarkV15 > columbiaV15) {
        denmark += 1;
    }

    //columbia # of victories in last 15 games
    if (columbiaV15 > croatiaV15) {
        columbia += 1;
    }
    
    if (columbiaV15 > belgiumV15) {
        columbia += 1;
    }

    if (columbiaV15 > denmarkV15) {
        columbia += 1;
    }

    //columbia # of defeats in last 15 games
    if (columbiaD15 > denmarkD15) {
        columbia -= 1;
    }
    
    if (columbiaD15 > belgiumD15) {
        columbia -= 1;
    }

    if (columbiaD15 > croatiaD15) {
        columbia -= 1;
    }

    //denmark # of defeats in last 15 games
    if (denmarkD15 > columbiaD15) {
        denmark -= 1;
    }
    
    if (denmarkD15 > belgiumD15) {
        denmark -= 1;
    }

    if (denmarkD15 > croatiaD15) {
        denmark -= 1;
    }

    //belgium # of defeats in last 15 games
    if (belgiumD15 > columbiaD15) {
        belgium -= 1;
    }
    
    if (belgiumD15 > denmarkD15) {
        belgium -= 1;
    }

    if (belgiumD15 > croatiaD15) {
        belgium -= 1;
    }

    //croatia # of defeats in last 15 games
    if (croatiaD15 > columbiaD15) {
        croatia -= 1;
    }
    
    if (croatiaD15 > denmarkD15) {
        croatia -= 1;
    }

    if (croatiaD15 > belgiumD15) {
        croatia -= 1;
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


    //1st place results
    if (columbia > denmark && columbia > croatia && columbia > belgium) {
        cout << "Columbia is the winner of Group B" << endl;
        Q1groupB = columbia;
        Q1groupBattack = columbiaattack;
        Q1groupBmidfield = columbiamidfield;
        Q1groupBdeffence = columbiadeffence;
        FQ1groupB = "Columbia";
    }

    else if (denmark > columbia && denmark > croatia && denmark > belgium) {
        cout << "Denmark is the winner of Group B" << endl;
        Q1groupB = denmark;
        Q1groupBattack = denmarkattack;
        Q1groupBmidfield = denmarkmidfield;
        Q1groupBdeffence = denmarkdeffence;
        FQ1groupB = "Denmark";
    }

    else if (croatia > denmark && croatia > belgium && croatia > columbia) {
        cout << "Croatia is the winner of Group B" << endl;
        Q1groupB = croatia;
        Q1groupBattack = croatiaattack;
        Q1groupBmidfield = croatiamidfield;
        Q1groupBdeffence = croatiadeffence;
        FQ1groupB = "Croatia";
    }

    else if (belgium > denmark && belgium > croatia && belgium > columbia) {
        cout << "Belgium is the winner of Group B" << endl;
        Q1groupB = belgium;
        Q1groupBattack = belgiumattack;
        Q1groupBmidfield = belgiummidfield;
        Q1groupBdeffence = belgiumdeffence;
        FQ1groupB = "Belgium";
    }

    else {}

    //2nd place results
   
    //Columbia
    if (columbia > denmark && columbia > croatia && columbia < belgium) {
        cout << "Columbia is the second of Group B" << endl;
        Q2groupB = columbia;
        Q2groupBattack = columbiaattack;
        Q2groupBmidfield = columbiamidfield;
        Q2groupBdeffence = columbiadeffence;
        FQ2groupB = "Columbia";
    }

    else if (columbia > denmark && columbia < croatia && columbia > belgium) {
        cout << "Columbia is the second of Group B" << endl;
        Q2groupB = columbia;
        Q2groupBattack = columbiaattack;
        Q2groupBmidfield = columbiamidfield;
        Q2groupBdeffence = columbiadeffence;
        FQ2groupB = "Columbia";
    }

    else if (columbia < denmark && columbia > croatia && columbia > belgium) {
        cout << "Columbia is the second of Group B" << endl;
        Q2groupB = columbia;
        Q2groupBattack = columbiaattack;
        Q2groupBmidfield = columbiamidfield;
        Q2groupBdeffence = columbiadeffence;
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
        FQ2groupB = "Denmark";
    }

    else if (denmark > columbia && denmark < croatia && denmark > belgium) {
        cout << "Denmark is the second of Group B" << endl;
        Q2groupB = denmark;
        Q2groupBattack = denmarkattack;
        Q2groupBmidfield = denmarkmidfield;
        Q2groupBdeffence = denmarkdeffence;
        FQ2groupB = "Denmark";
    }

    else if (denmark < columbia && denmark > croatia && denmark > belgium) {
        cout << "Denmark is the second of Group B" << endl;
        Q2groupB = denmark;
        Q2groupBattack = denmarkattack;
        Q2groupBmidfield = denmarkmidfield;
        Q2groupBdeffence = denmarkdeffence;
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
        FQ2groupB = "Croatia";
    }

    else if (croatia > denmark && croatia < belgium && croatia > columbia) {
        cout << "Croatia is the second of Group B" << endl;
        Q2groupB = croatia;
        Q2groupBattack = croatiaattack;
        Q2groupBmidfield = croatiamidfield;
        Q2groupBdeffence = croatiadeffence;
        FQ2groupB = "Croatia";
    }

    else if (croatia < denmark && croatia > belgium && croatia > columbia) {
        cout << "Croatia is the second of Group B" << endl;
        Q2groupB = croatia;
        Q2groupBattack = croatiaattack;
        Q2groupBmidfield = croatiamidfield;
        Q2groupBdeffence = croatiadeffence;
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
        FQ2groupB = "Belgium";
    }

    else if (belgium > denmark && belgium < croatia && belgium > columbia) {
        cout << "Belgium is  the second of Group B" << endl;
        Q2groupB = belgium;
        Q2groupBattack = belgiumattack;
        Q2groupBmidfield = belgiummidfield;
        Q2groupBdeffence = belgiumdeffence;
        FQ2groupB = "Belgium";
    }

    else if (belgium < denmark && belgium > croatia && belgium > columbia) {
        cout << "Belgium is the second of Group B" << endl;
        Q2groupB = belgium;
        Q2groupBattack = belgiumattack;
        Q2groupBmidfield = belgiummidfield;
        Q2groupBdeffence = belgiumdeffence;
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

    //Italy # of goals scored in last 15 games
    if (italy15 > portugal15) {
        italy += 1;
    }
    
    if (italy15 > australia15) {
        italy += 1;
    }

    if (italy15 > iran15) {
        italy += 1;
    }

    //Portugal # of goals scored in last 15 games
    if (portugal15 > italy15) {
        portugal += 1;
    }
    
    if (portugal15 > australia15) {
        portugal += 1;
    }

    if (portugal15 > iran15) {
        portugal += 1;
    }

    //australia # of goals scored in last 15 games
    if (australia15 > italy15) {
        australia += 1;
    }
    
    if (australia15 > portugal15) {
        australia += 1;
    }

    if (australia15 > iran15) {
        australia += 1;
    }

    //iran # of goals scored in last 15 games
    if (iran15 > italy15) {
        iran += 1;
    }
    
    if (iran15 > portugal15) {
        iran += 1;
    }

    if (iran15 > australia15) {
        iran += 1;
    }

    //iran # of goals conceded in last 15 games
    if (iranC15 > australiaC15) {
        iran -= 1;
    }
    
    if (iranC15 > portugalC15) {
        iran -= 1;
    }

    if (iranC15 > italyC15) {
        iran -= 1;
    }

    //australia # of goals conceded in last 15 games
    if (australiaC15 > iranC15) {
        australia -= 1;
    }
    
    if (australiaC15 > portugalC15) {
        australia -= 1;
    }

    if (australiaC15 > italyC15) {
        australia -= 1;
    }

    //portugal # of goals conceded in last 15 games
    if (portugalC15 > iranC15) {
        portugal -= 1;
    }
    
    if (portugalC15 > australiaC15) {
        portugal -= 1;
    }

    if (portugalC15 > italyC15) {
        portugal -= 1;
    }

    //italy # of goals conceded in last 15 games
    if (italyC15 > iranC15) {
        italy -= 1;
    }
    
    if (italyC15 > australiaC15) {
        italy -= 1;
    }

    if (italyC15 > portugalC15) {
        italy -= 1;
    }

    //italy # of victories in last 15 games
    if (italyV15 > portugalV15) {
        italy += 1;
    }
    
    if (italyV15 > australiaV15) {
        italy += 1;
    }

    if (italyV15 > iranV15) {
        italy += 1;
    }

    //portugal # of victories in last 15 games
    if (portugalV15 > italyV15) {
        portugal += 1;
    }
    
    if (portugalV15 > australiaV15) {
        portugal += 1;
    }

    if (portugalV15 > iranV15) {
        portugal += 1;
    }

    //australia # of victories in last 15 games
    if (australiaV15 > italyV15) {
        australia += 1;
    }
    
    if (australiaV15 > portugalV15) {
        australia += 1;
    }

    if (australiaV15 > iranV15) {
        australia += 1;
    }

    //iran # of victories in last 15 games
    if (iranV15 > italyV15) {
        iran += 1;
    }
    
    if (iranV15 > portugalV15) {
        iran += 1;
    }

    if (iranV15 > australiaV15) {
        iran += 1;
    }

    //iran # of defeats in last 15 games
    if (iranD15 > australiaD15) {
        iran -= 1;
    }
    
    if (iranD15 > portugalD15) {
        iran -= 1;
    }

    if (iranD15 > italyD15) {
        iran -= 1;
    }

    //australia # of defeats in last 15 games
    if (australiaD15 > iranD15) {
        australia -= 1;
    }
    
    if (australiaD15 > portugalD15) {
        australia -= 1;
    }

    if (australiaD15 > italyD15) {
        australia -= 1;
    }

    //portugal # of defeats in last 15 games
    if (portugalD15 > iranD15) {
        portugal -= 1;
    }
    
    if (portugalD15 > australiaD15) {
        portugal -= 1;
    }

    if (portugalD15 > italyD15) {
        portugal -= 1;
    }

    //italy # of defeats in last 15 games
    if (italyD15 > iranD15) {
        italy -= 1;
    }
    
    if (italyD15 > australiaD15) {
        italy -= 1;
    }

    if (italyD15 > portugalD15) {
        italy -= 1;
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
        FQ1groupA = "Italy";
    }

    else if (portugal > italy && portugal > australia && portugal > iran) {
        cout << "Portugal is the winner of Group A" << endl;
        Q1groupA = portugal;
        Q1groupAattack = portugalattack;
        Q1groupAmidfield = portugalmidfield;
        Q1groupAdeffence = portugaldeffence;
        FQ1groupA = "Portugal";
    }

    else if (australia > italy && australia > portugal && australia > iran) {
        cout << "Australia is the winner of Group A" << endl;
        Q1groupA = australia;
        Q1groupAattack = australiaattack;
        Q1groupAmidfield = australiamidfield;
        Q1groupAdeffence = australiadeffence;
        FQ1groupA = "Australia";
    }

    else if (iran > italy && iran > portugal && iran > australia) {
        cout << "Iran is the winner of Group A" << endl;
        Q1groupA = iran;
        Q1groupAattack = iranattack;
        Q1groupAmidfield = iranmidfield;
        Q1groupAdeffence = irandeffence;
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
        FQ2groupA = "Italy";
    }

    else if (italy > portugal && italy < australia && italy > iran) {
        cout << "Italy is the second of Group A" << endl;
        Q2groupA = italy;
        Q2groupAattack = italyattack;
        Q2groupAmidfield = italymidfield;
        Q2groupAdeffence = italydeffence;
        FQ2groupA = "Italy";
    }

    else if (italy < portugal && italy > australia && italy > iran) {
        cout << "Italy is the second of Group A" << endl;
        Q2groupA = italy;
        Q2groupAattack = italyattack;
        Q2groupAmidfield = italymidfield;
        Q2groupAdeffence = italydeffence;
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
        FQ2groupA = "Portugal";
    }

    else if (portugal > italy && portugal < australia && portugal > iran) {
        cout << "Portugal is the second of Group A" << endl;
        Q2groupA = portugal;
        Q2groupAattack = portugalattack;
        Q2groupAmidfield = portugalmidfield;
        Q2groupAdeffence = portugaldeffence;
        FQ2groupA = "Portugal";
    }

    else if (portugal < italy && portugal > australia && portugal > iran) {
        cout << "Portugal is the second of Group A" << endl;
        Q2groupA = portugal;
        Q2groupAattack = portugalattack;
        Q2groupAmidfield = portugalmidfield;
        Q2groupAdeffence = portugaldeffence;
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
        FQ2groupA = "Australia";
    }

    else if (australia > italy && australia < portugal && australia > iran) {
        cout << "Australia is the second of Group A" << endl;
        Q2groupA = australia;
        Q2groupAattack = australiaattack;
        Q2groupAmidfield = australiamidfield;
        Q2groupAdeffence = australiadeffence;
        FQ2groupA = "Australia";
    }

    else if (australia < italy && australia > portugal && australia > iran) {
        cout << "Australia is the second of Group A" << endl;
        Q2groupA = australia;
        Q2groupAattack = australiaattack;
        Q2groupAmidfield = australiamidfield;
        Q2groupAdeffence = australiadeffence;
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
        FQ2groupA = "Iran";
    }

    else if (iran > italy && iran < portugal && iran > australia) {
        cout << "Iran is the second of Group A" << endl;
        Q2groupA = iran;
        Q2groupAattack = iranattack;
        Q2groupAmidfield = iranmidfield;
        Q2groupAdeffence = irandeffence;
        FQ2groupA = "Iran";
    }

    else if (iran < italy && iran > portugal && iran > australia) {
        cout << "Iran is the second of Group A" << endl;
        Q2groupA = iran;
        Q2groupAattack = iranattack;
        Q2groupAmidfield = iranmidfield;
        Q2groupAdeffence = irandeffence;
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

    cout << endl;
    
    //Round 1 match results
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
    
    























}
