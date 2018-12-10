#include <iostream>
using namespace std;

int main () {

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

    //1st place results
    if (columbia > denmark && columbia > croatia && columbia > belgium) {
        cout << "Columbia is the winner of Group B" << endl;
        Q1groupB = columbia;
        Q1groupBattack = columbiaattack;
        Q1groupBmidfield = columbiamidfield;
        Q1groupBdeffence = columbiadeffence;
        FQ1groupB = "Columbia";
        FR1game2F = "Columbia";
        FR1game2T = "Columbia";
    }

    else if (denmark > columbia && denmark > croatia && denmark > belgium) {
        cout << "Denmark is the winner of Group B" << endl;
        Q1groupB = denmark;
        Q1groupBattack = denmarkattack;
        Q1groupBmidfield = denmarkmidfield;
        Q1groupBdeffence = denmarkdeffence;
        FQ1groupB = "Denmark";
        FR1game2F = "Denmark";
        FR1game2T = "Denmark";
    }

    else if (croatia > denmark && croatia > belgium && croatia > columbia) {
        cout << "Croatia is the winner of Group B" << endl;
        Q1groupB = croatia;
        Q1groupBattack = croatiaattack;
        Q1groupBmidfield = croatiamidfield;
        Q1groupBdeffence = croatiadeffence;
        FQ1groupB = "Croatia";
        FR1game2F = "Croatia";
        FR1game2T = "Croatia";
    }

    else if (belgium > denmark && belgium > croatia && belgium > columbia) {
        cout << "Belgium is the winner of Group B" << endl;
        Q1groupB = belgium;
        Q1groupBattack = belgiumattack;
        Q1groupBmidfield = belgiummidfield;
        Q1groupBdeffence = belgiumdeffence;
        FQ1groupB = "Belgium";
        FR1game2F = "Belgium";
        FR1game2T = "Belgium";
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
        FR1game1F = "Columbia";
        FR1game1T = "Columbia";
    }

    else if (columbia > denmark && columbia < croatia && columbia > belgium) {
        cout << "Columbia is the second of Group B" << endl;
        Q2groupB = columbia;
        Q2groupBattack = columbiaattack;
        Q2groupBmidfield = columbiamidfield;
        Q2groupBdeffence = columbiadeffence;
        FQ2groupB = "Columbia";
        FR1game1F = "Columbia";
        FR1game1T = "Columbia";
    }

    else if (columbia < denmark && columbia > croatia && columbia > belgium) {
        cout << "Columbia is the second of Group B" << endl;
        Q2groupB = columbia;
        Q2groupBattack = columbiaattack;
        Q2groupBmidfield = columbiamidfield;
        Q2groupBdeffence = columbiadeffence;
        FQ2groupB = "Columbia";
        FR1game1F = "Columbia";
        FR1game1T = "Columbia";
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
        FR1game1F = "Denmark";
        FR1game1T = "Denmark";
    }

    else if (denmark > columbia && denmark < croatia && denmark > belgium) {
        cout << "Denmark is the second of Group B" << endl;
        Q2groupB = denmark;
        Q2groupBattack = denmarkattack;
        Q2groupBmidfield = denmarkmidfield;
        Q2groupBdeffence = denmarkdeffence;
        FQ2groupB = "Denmark";
        FR1game1F = "Denmark";
        FR1game1T = "Denmark";
    }

    else if (denmark < columbia && denmark > croatia && denmark > belgium) {
        cout << "Denmark is the second of Group B" << endl;
        Q2groupB = denmark;
        Q2groupBattack = denmarkattack;
        Q2groupBmidfield = denmarkmidfield;
        Q2groupBdeffence = denmarkdeffence;
        FQ2groupB = "Denmark";
        FR1game1F = "Denmark";
        FR1game1T = "Denmark";
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
        FR1game1F = "Croatia";
        FR1game1T = "Croatia";
    }

    else if (croatia > denmark && croatia < belgium && croatia > columbia) {
        cout << "Croatia is the second of Group B" << endl;
        Q2groupB = croatia;
        Q2groupBattack = croatiaattack;
        Q2groupBmidfield = croatiamidfield;
        Q2groupBdeffence = croatiadeffence;
        FQ2groupB = "Croatia";
        FR1game1F = "Croatia";
        FR1game1T = "Croatia";
    }

    else if (croatia < denmark && croatia > belgium && croatia > columbia) {
        cout << "Croatia is the second of Group B" << endl;
        Q2groupB = croatia;
        Q2groupBattack = croatiaattack;
        Q2groupBmidfield = croatiamidfield;
        Q2groupBdeffence = croatiadeffence;
        FQ2groupB = "Croatia";
        FR1game1F = "Croatia";
        FR1game1T = "Croatia";
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
        FR1game1F = "Belgium";
        FR1game1T = "Belgium";
    }

    else if (belgium > denmark && belgium < croatia && belgium > columbia) {
        cout << "Belgium is  the second of Group B" << endl;
        Q2groupB = belgium;
        Q2groupBattack = belgiumattack;
        Q2groupBmidfield = belgiummidfield;
        Q2groupBdeffence = belgiumdeffence;
        FQ2groupB = "Belgium";
        FR1game1F = "Belgium";
        FR1game1T = "Belgium";
    }

    else if (belgium < denmark && belgium > croatia && belgium > columbia) {
        cout << "Belgium is the second of Group B" << endl;
        Q2groupB = belgium;
        Q2groupBattack = belgiumattack;
        Q2groupBmidfield = belgiummidfield;
        Q2groupBdeffence = belgiumdeffence;
        FQ2groupB = "Belgium";
        FR1game1F = "Belgium";
        FR1game1T = "Belgium";
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
        FR1game1F = "Portugal";
        FR1game1T = "Portugal";
    }

    else if (australia > italy && australia > portugal && australia > iran) {
        cout << "Australia is the winner of Group A" << endl;
        Q1groupA = australia;
        Q1groupAattack = australiaattack;
        Q1groupAmidfield = australiamidfield;
        Q1groupAdeffence = australiadeffence;
        FQ1groupA = "Australia";
        FR1game1F = "Australia";
        FR1game1T = "Australia";
    }

    else if (iran > italy && iran > portugal && iran > australia) {
        cout << "Iran is the winner of Group A" << endl;
        Q1groupA = iran;
        Q1groupAattack = iranattack;
        Q1groupAmidfield = iranmidfield;
        Q1groupAdeffence = irandeffence;
        FQ1groupA = "Iran";
        FR1game1F = "Iran";
        FR1game1T = "Iran";
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
        FR1game2F = "Italy";
        FR1game2T = "Italy";
    }

    else if (italy > portugal && italy < australia && italy > iran) {
        cout << "Italy is the second of Group A" << endl;
        Q2groupA = italy;
        Q2groupAattack = italyattack;
        Q2groupAmidfield = italymidfield;
        Q2groupAdeffence = italydeffence;
        FQ2groupA = "Italy";
        FR1game2F = "Italy";
        FR1game2T = "Italy";
    }

    else if (italy < portugal && italy > australia && italy > iran) {
        cout << "Italy is the second of Group A" << endl;
        Q2groupA = italy;
        Q2groupAattack = italyattack;
        Q2groupAmidfield = italymidfield;
        Q2groupAdeffence = italydeffence;
        FQ2groupA = "Italy";
        FR1game2F = "Italy";
        FR1game2T = "Italy";
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
        FR1game2F = "Portugal";
        FR1game2T = "Portugal";
    }

    else if (portugal > italy && portugal < australia && portugal > iran) {
        cout << "Portugal is the second of Group A" << endl;
        Q2groupA = portugal;
        Q2groupAattack = portugalattack;
        Q2groupAmidfield = portugalmidfield;
        Q2groupAdeffence = portugaldeffence;
        FQ2groupA = "Portugal";
        FR1game2F = "Portugal";
        FR1game2T = "Portugal";
    }

    else if (portugal < italy && portugal > australia && portugal > iran) {
        cout << "Portugal is the second of Group A" << endl;
        Q2groupA = portugal;
        Q2groupAattack = portugalattack;
        Q2groupAmidfield = portugalmidfield;
        Q2groupAdeffence = portugaldeffence;
        FQ2groupA = "Portugal";
        FR1game2F = "Portugal";
        FR1game2T = "Portugal";
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
        FR1game2F = "Australia";
        FR1game2T = "Australia";
    }

    else if (australia > italy && australia < portugal && australia > iran) {
        cout << "Australia is the second of Group A" << endl;
        Q2groupA = australia;
        Q2groupAattack = australiaattack;
        Q2groupAmidfield = australiamidfield;
        Q2groupAdeffence = australiadeffence;
        FQ2groupA = "Australia";
        FR1game2F = "Australia";
        FR1game2T = "Australia";
    }

    else if (australia < italy && australia > portugal && australia > iran) {
        cout << "Australia is the second of Group A" << endl;
        Q2groupA = australia;
        Q2groupAattack = australiaattack;
        Q2groupAmidfield = australiamidfield;
        Q2groupAdeffence = australiadeffence;
        FQ2groupA = "Australia";
        FR1game2F = "Australia";
        FR1game2T = "Australia";
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
        FR1game2F = "Iran";
        FR1game2T = "Iran";
    }

    else if (iran > italy && iran < portugal && iran > australia) {
        cout << "Iran is the second of Group A" << endl;
        Q2groupA = iran;
        Q2groupAattack = iranattack;
        Q2groupAmidfield = iranmidfield;
        Q2groupAdeffence = irandeffence;
        FQ2groupA = "Iran";
        FR1game2F = "Iran";
        FR1game2T = "Iran";
    }

    else if (iran < italy && iran > portugal && iran > australia) {
        cout << "Iran is the second of Group A" << endl;
        Q2groupA = iran;
        Q2groupAattack = iranattack;
        Q2groupAmidfield = iranmidfield;
        Q2groupAdeffence = irandeffence;
        FQ2groupA = "Iran";
        FR1game2F = "Iran";
        FR1game2T = "Iran";
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
