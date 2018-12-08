# CS-Final-Project
The work area for CS Final Project

#include <iostream>
using namespace std;

int main () {

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
    }

    else if (portugal > italy && portugal > australia && portugal > iran) {
        cout << "Portugal is the winner of Group A" << endl;
    }

    else if (australia > italy && australia > portugal && australia > iran) {
        cout << "Australia is the winner of Group A" << endl;
    }

    else if (iran > italy && iran > portugal && iran > australia) {
        cout << "Iran is the winner of Group A" << endl;
    }

    //2nd place results
   
    //Italy
    if (italy > portugal && italy > australia && italy < iran) {
        cout << "Italy is the second of Group A" << endl;
    }

    else if (italy > portugal && italy < australia && italy > iran) {
        cout << "Italy is the second of Group A" << endl;
    }

    else if (italy < portugal && italy > australia && italy > iran) {
        cout << "Italy is the second of Group A" << endl;
    }

    //Portugal
    if (portugal > italy && portugal > australia && portugal < iran) {
        cout << "Portugal is the second of Group A" << endl;
    }

    else if (portugal > italy && portugal < australia && portugal > iran) {
        cout << "Portugal is the second of Group A" << endl;
    }

    else if (portugal < italy && portugal > australia && portugal > iran) {
        cout << "Portugal is the second of Group A" << endl;
    }

    //Australia
    if (australia > italy && australia > portugal && australia < iran) {
        cout << "Australia is the second of Group A" << endl;
    }

    else if (australia > italy && australia < portugal && australia > iran) {
        cout << "Australia is the second of Group A" << endl;
    }

    else if (australia < italy && australia > portugal && australia > iran) {
        cout << "Australia is the second of Group A" << endl;
    }

    //Iran
    if (iran > italy && iran > portugal && iran < australia) {
        cout << "Iran is the second of Group A" << endl;
    }

    else if (iran > italy && iran < portugal && iran > australia) {
        cout << "Iran is the second of Group A" << endl;
    }

    else if (iran < italy && iran > portugal && iran > australia) {
        cout << "Iran is the second of Group A" << endl;
    }

    
    























}
