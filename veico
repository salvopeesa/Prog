#ifndef VEICOLI_H
#define VEICOLI_H

#include<iostream>
#include<string>

using namespace std;

class Veicolo {
    protected:
    int cilindrata;
    string type;

    public:
        Veicolo(int cilindrata, string type) :  cilindrata(cilindrata), type(type) {}
    int getCilindrata() {
        return this->cilindrata;
    }
    ostream& put(ostream& os) {
        os << "Tipo: " << type << " ,cilindrata = " << getCilindrata() << endl;
    }
};

ostream& operator<<(ostream& os, Veicolo& w) {
    return w.put(os);
}

class Auto {
    public:
        Auto(int cilindrata, int type) :veicolo(cilindrata, type) {}
};
class Moto {
    public:
        Moto(int cilindrata, int type) :veicolo(cilindrata, type) {}

};
class Barca{
    public:
        Barca(int cilindrata, int type) :veicolo(cilindrata, type) {}
};

#endif