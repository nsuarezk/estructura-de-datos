# estructura-de-datos

#pragma once
#include "Persona.h"

class Administrativo: public Persona
{
private:
	int Sueldo;

public:
	Administrativo(void);

	void Get_Sueldo (int _sueldo)
	{
		Sueldo = _sueldo;
	}

	~Administrativo(void);

};




#pragma once
#include "Persona.h"
#include <iostream>

using namespace std;

class Docente: public Persona
{
private:
	int hora;

public:
	Docente(void);
	~Docente(void);

	void gethora (int _hora)
	{
		hora = _hora;
	}
};




#pragma once
#include <string>

using namespace std;

class Persona
{
protected:
	int CI;
	string Nombre;
	int ID;

public:
	void setCI (int n);
	void setNombre (string N);
	void setID (int I);

};





#include "StdAfx.h"
#include "Persona.h"
#include <string>

using namespace std;

void Persona::setCI (int n)
{ 
	CI = n;
}

void Persona::setNombre (string N)
{
	Nombre = N;
}

void Persona::setID (int I)
{
	ID = I;
}






// EjemploPersona.cpp : Defines the entry point for the console application.
//

#include "stdafx.h"
#include <iostream>
#include "Administrativo.h"
#include "conio.h"
#include "string"


using namespace std;

void main ()
{
	string n;
	int c, s, I;
	cout << "Ingrese el nombre: " << endl;
	getline (cin, n);
	cout << "Ingrese el CI: " << endl;
	cin >> c;
	cout << "Ingrese el ID: " << endl;
	cin >> I;
	cout << "Ingrese el Sueldo: " << endl;
	cin >> s;

}
