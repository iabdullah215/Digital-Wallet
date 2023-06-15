#include <iostream>
#include <conio.h>
#include <fstream>
using namespace std;
int mask();
ofstream final;
void id_number(string n);
int main()
{
	string user_name, c_pin, c_number, phone, name, b_number, company;
	int pin, balance = 100000, option, bank, bank_add, sim, load, bill, bill_pay, back,cas;
	char pwd[20];
	cout << endl;
	cout << "                                                                    MAM SARA ASIF (sara_88)" << endl;
	cout << "                                                                MAM MOMINA SADAF (pflab88fail)" << endl;
	cout << endl;
	cout << "                                                                     USERNAME: ";
	cin >> user_name;
	if (user_name == "sara_88" || user_name == "pflab88fail")
	{
		mask();
		cout <<endl<< endl;
		    cout << "                           ----------------------------------------------------------------------------------------------------------  " << endl;
			cout << "                           | **    **  **    ********  ******  *******     **       **  *******  **      **       ******  ********  |  " << endl;
			cout << "                           |  **    **  **       **     **   *  **   **     **       **  **   **  **      **       **         **    |  "  << endl;
			cout << "                           |   **    **  **       **     ******  *******     **  **   **  *******  **      **       ******     **   |  "  << endl;
			cout << "                           |    **    **  **       **     ** **   **   **     ** ** ** **  **   **  **      **       **         **  |  " << endl;
			cout << "                           |     ********  *******  **     **  **  **   **     ****   ****  **   **  ******* *******  ******     ** |  " << endl;
			cout << "                           ----------------------------------------------------------------------------------------------------------  " << endl;
			cout << endl;
			cout << endl;
			cout << "WELCOME " << user_name << " TO ULTRA WALLET" << endl;
			cout << endl;
			cout << "CUTTENT BALANCE: ";
			cout << balance << endl;
			cout << endl;
		

				cout << "                                                            * ---------M A I N  M E N U--------- *" << endl << endl;
				cout << "SELECT ANY ONE OF THE FOLLOWING OPTIONS" << endl;
				cout << "(1) ADD BALANCE" << endl;
				cout << "(2) SEND MONEY" << endl;
				cout << "(3) EASY LOAD" << endl;
				cout << "(4) BILL PAYMENT" << endl;
				cout << endl;
				cout << "ENTER YOUR OPTION NUMBER: ";
				cin >> option;
				cout << endl;
				switch (option)
				{
				case 1:
					cout << "                                                            * ---------A D D  M O N E Y--------- *" << endl << endl;
					cout << endl;
					cout << "CHOOSE YOU BANK" << endl;
					cout << "(1) ALLIED BANK" << endl;
					cout << "(2) UBL BANK" << endl;
					cout << "(3) HBL BANK" << endl;
					cout << endl;
					cout << "ENTER YOUR BANK NUMBER: ";
					cin >> bank;
					cout << endl;
					if (bank == 1 || bank == 2 || bank == 3)
					{
						cout << "                                                           CREDIT CARD NUMBER: ";
						cin >> c_number;

						if (c_number.size() == 14)
						{
							id_number(c_number);
							
							mask();
								cout<<endl;
								cout << "ULTRA WALLET USERNAME: " << user_name;
								cout << endl;
								cout << "HOW MUCH MONEY YOU WANT TO ADD: ";
								cin >> bank_add;
								cout << endl;
								cout << "BALANCE BEFORE TRANCECTION: " << balance << endl;
								cout << endl;
								cas = balance + bank_add;
								cout << "BALANCE AFTER TRNCECTION: " << cas << endl;
								cout << user_name << " YOU SUCCESSFULLY HAVE ADDED RS: " << bank_add << " TO YOUR ULTRA WALLET ACCOUNT" << endl;
							

								ofstream add_money;
								add_money.open("add_money.txt", ios::app);
								if (add_money.is_open())
								{
									add_money << c_number << endl;
								}

								ofstream final;
								final.open("final.txt", ios::app);
								final << user_name << " YOU SUCCESSFULLY HAVE ADDED RS: " << bank_add << " TO YOUR ULTRA WALLET ACCOUNT" << endl;
								final.close();
							}
							else // unvalid cradit card pin
							{
								cout << "UNVALID PIN";
							}
						}
						else // unvalid cradit card number
						{
							cout << "UNVALID CRADIT CARD NUMBER";
						}
				
					break; // case 1 ( add money ) ends here
				case 2:
					cout << "                                                            * ---------S E N D  M O N E Y--------- *" << endl << endl;
					cout << endl;
					cout << "CHOOSE YOU BANK" << endl;
					cout << "(1) ALLIED BANK" << endl;
					cout << "(2) UBL BANK" << endl;
					cout << "(3) HBL BANK" << endl;
					cout << endl;
					cout << "ENTER YOUR BANK NUMBER: ";
					cin >> bank;
					cout << endl;
					if (bank == 1 || bank == 2 || bank == 3)
					{
						cout << "                                                           CRADIT CARD NUMBER: ";
						cin >> c_number;
						if (c_number.size() == 14)
						{
							id_number(c_number);
							cout << "ULTRA WALLET USERNAME: ";
							if (user_name == "sara_88")
							{
								cout << " pflab88fail" << endl;
							}
							else if (user_name == "pflab88fail")
							{
								cout << "sara_88" << endl;
							}
							else
							{
								cout << "ERROR...";
							}
							cout << endl;
							cout << "HOW MUCH MONEY YOU WANT TO SEND: ";
							cin >> bank_add;
							cout << endl;
							if (bank_add > balance)
							{
								cout << "NOT ENOUGH BALANCE";
							}
							else if (bank_add <= balance)
							{
								cout << "BALANCE BEFORE TRANCECTION: " << balance << endl;
								cout << endl;
								cas = balance - bank_add;
								cout << "BALANCE AFTER TRACTION: " << cas;

								ofstream send_money;
								send_money.open("send_money.txt", ios::app);
								if (send_money.is_open())
								{
									send_money << c_number << endl;
								}

								ofstream final;
								final.open("final.txt", ios::app);
								final << "YOU HAVE SUCCESSFULLY SENT " << bank_add << endl;

							}
						}
						else // unvalid cradit card number
						{
							cout << "UNVALID CRADIT CARD NUMBER";
						}
					}
					else // unvalid bank number
					{
						cout << "UNVALID NUMBER";
					}
					break; // case 2 ( add money ) ends here
				case 3:
					cout << "                                                            * ---------E A S Y  L O A D--------- *" << endl << endl;
					cout << endl;
					cout << "CHOOSE SIM" << endl;
					cout << "(1) ZONG" << endl;
					cout << "(2) JAZZ" << endl;
					cout << "(3) UFONE" << endl;
					cout << endl;
					cout << "ENTER SIM NUMBER: ";
					cin >> sim;
					cout << endl;
					if (sim == 1 || sim == 2 || sim == 3)
					{
						cout << "ENTER PHONE NUMBER: +92";
						cin >> phone;
						if (phone.size() == 10)
						{
							cout << "NAME: ";
							cin >> name;
							cout << endl;
							cout << "HOW MUCH LOAD YOU WANT TO SEND: ";
							cin >> load;
							cout << endl;
							if (load > balance)
							{
								cout << "NOT ENOUGH BALANCE";
							}
							else if (load <= balance)
							{
								cout << "BALANCE BEFORE EASYLOAD: " << balance << endl;
								cout << endl;
								cas= balance - load;
								cout << "BALANCE AFTER EASYLOAD: " << cas;
								cout << endl;
								cout << user_name << " HAS SUCCESSFULLY SENT EASY LOAD OF RS:" << load << " TO " << name << " 0" << phone << "." << endl;

								ofstream easy_load;
								easy_load.open("easy_load.txt", ios::app);
								if (easy_load.is_open())
								{
									easy_load << phone << " " << name << endl;
								}

								ofstream final;
								final.open("final.txt" , ios::app);
								final << user_name << " HAS SUCCESSFULLY SENT EASY LOAD OF RS:" << load << " TO " << name << " " << phone << "." << endl;
							}
						}
						else // unvalid phone number
						{
							cout << "UNVALID PHONE NUMBER NUMBER";
						}
					}
					else // unvalid sim number
					{
						cout << "UNVALID SIM NUMBER";
					}
					break; // case 3 ( easy-load ) ends here
				case 4:
					cout << "                                                          * ---------B I L L  P A Y M E N T--------- *" << endl << endl;
					cout << endl;
					cout << "CHOOSE AN OPTION" << endl;
					cout << "(1) GAS BILL" << endl;
					cout << "(2) WATER BILL" << endl;
					cout << "(3) ELECTRICAL BILL" << endl;
					cout << endl;
					cout << "ENTER A NUMBER: ";
					cin >> bill;
					cout << endl;
					if (bill == 1 || bill == 2 || bill == 3)
					{
						cout << "ENTER YOUR BILL(10) NUMBER: ";
						cin >> b_number;
						if (b_number.size() == 10)
						{
							id_number(b_number);
							cout << "NAME: ";
							cin >> name;
							cout << "ENTER COMPANY NAME TO WHOM YOU ARE REGISTERED WITH: ";
							cin >> company;
							cout << endl;
							cout << "HOW MUCH BILL DO YOU WANT TO PAY: ";
							cin >> bill_pay;
							cout << endl;
							if (bill_pay > balance)
							{
								cout << "NOT ENOUGH BALANCE";
							}
							else if (bill_pay <= balance)
							{
								cout << "BALANCE BEFORE BILL PAYMENT: " << balance << endl;
								cout << endl;
								cas=balance - bill_pay;
								cout << "BALANCE AFTER BILL PAYMENT: " << cas;
								cout << endl;
								cout << name << " HAS SUCCESSFULLY PAYED THEIR BILL OF RS:" << bill_pay << " TO " << company << "." << endl;

								ofstream bill_payment;
								bill_payment.open("bill_payment.txt", ios::app);
								if (bill_payment.is_open())
								{
									bill_payment << name << " " << company << endl;
								}

								ofstream final;
								final.open("final.txt",ios::app);
								final << name << " HAS SUCCESSFULLY PAYED THEIR BILL OF RS:" << bill_pay << " TO " << company << "." << endl;
								final.close();
							}
						}
						else // unvalid bill number
						{
							cout << "UNVALID BILL NUMBER";
						}
					}
					else // unvalid option number
					{
						cout << "UNVALID OPTION";
					}
					break; // case 4 ( bill payment ) ends here
				default:
				{
					cout << "UNVALID ENTERY...";
					break;
				}
				}

				cout << endl; cout << endl;
				cout << "TO GO BACK TO THE MAIN MENU PRESS [ 1 ] EITHER PRESS [ 0 ]" << endl << endl;
				cin >> back;
			 
			if (back == 1)
{
	do
	{
		cout << "                                                            * ---------M A I N  M E N U--------- *" << endl << endl;
				cout << "SELECT ANY ONE OF THE FOLLOWING OPTIONS" << endl;
				cout << "(1) ADD BALANCE" << endl;
				cout << "(2) SEND MONEY" << endl;
				cout << "(3) EASY LOAD" << endl;
				cout << "(4) BILL PAYMENT" << endl;
				cout << endl;
				cout << "ENTER YOUR OPTION NUMBER: ";
				cin >> option;
				cout << endl;
				switch (option)
				{
				case 1:
					cout << "                                                            * ---------A D D  M O N E Y--------- *" << endl << endl;
					cout << endl;
					cout << "CHOOSE YOU BANK" << endl;
					cout << "(1) ALLIED BANK" << endl;
					cout << "(2) UBL BANK" << endl;
					cout << "(3) HBL BANK" << endl;
					cout << endl;
					cout << "ENTER YOUR BANK NUMBER: ";
					cin >> bank;
					cout << endl;
					if (bank == 1 || bank == 2 || bank == 3)
					{
						cout << "                                                           CRADIT CARD NUMBER: ";
						cin >> c_number;

						if (c_number.size() == 14)
						{
							id_number(c_number);
							
							mask();
								cout<<endl;
								cout << "ULTRA WALLET USERNAME: " << user_name;
								cout << endl;
								cout << "HOW MUCH MONEY YOU WANT TO ADD: ";
								cin >> bank_add;
								cout << endl;
								cout << "BALANCE BEFORE TRANCECTION: " << cas << endl;
								cout << endl;
								cas+= bank_add;
								cout << "BALANCE AFTER TRNCECTION: " << cas << endl;
								cout << user_name << " YOU SUCCESSFULLY HAVE ADDED RS: " << bank_add << " TO YOUR ULTRA WALLET ACCOUNT" << endl;

								ofstream add_money;
								add_money.open("add_money.txt", ios::app);
								if (add_money.is_open())
								{
									add_money << c_number << endl;
								}

								ofstream final;
								final.open("final.txt", ios::app);
								final << user_name << " YOU SUCCESSFULLY HAVE ADDED RS: " << bank_add << " TO YOUR ULTRA WALLET ACCOUNT" << endl;
								final.close();
							}
							else // unvalid cradit card pin
							{
								cout << "UNVALID PIN";
							}
						}
						else // unvalid cradit card number
						{
							cout << "UNVALID CRADIT CARD NUMBER";
						}
				
					break; // case 1 ( add money ) ends here
				case 2:
					cout << "                                                            * ---------S E N D  M O N E Y--------- *" << endl << endl;
					cout << endl;
					cout << "CHOOSE YOU BANK" << endl;
					cout << "(1) ALLIED BANK" << endl;
					cout << "(2) UBL BANK" << endl;
					cout << "(3) HBL BANK" << endl;
					cout << endl;
					cout << "ENTER YOUR BANK NUMBER: ";
					cin >> bank;
					cout << endl;
					if (bank == 1 || bank == 2 || bank == 3)
					{
						cout << "                                                           CRADIT CARD NUMBER: ";
						cin >> c_number;
						if (c_number.size() == 14)
						{
							id_number(c_number);
							cout << "ULTRA WALLET USERNAME: ";
							if (user_name == "sara_88")
							{
								cout << " pflab88fail" << endl;
							}
							else if (user_name == "pflab88fail")
							{
								cout << "sara_88" << endl;
							}
							else
							{
								cout << "ERROR...";
							}
							cout << endl;
							cout << "HOW MUCH MONEY YOU WANT TO SEND: ";
							cin >> bank_add;
							cout << endl;
							if (bank_add > cas)
							{
								cout << "NOT ENOUGH BALANCE";
							}
							else if (bank_add <= cas)
							{
								cout << "BALANCE BEFORE TRANCECTION: " << cas << endl;
								cout << endl;
								cas -= bank_add;
								cout << "BALANCE AFTER TRACTION: " << cas;

								ofstream send_money;
								send_money.open("send_money.txt", ios::app);
								if (send_money.is_open())
								{
									send_money << c_number << endl;
								}

								ofstream final;
								final.open("final.txt", ios::app);
								final << "YOU HAVE SUCCESSFULLY SENT " << bank_add << endl;

							}
						}
						else // unvalid cradit card number
						{
							cout << "UNVALID CRADIT CARD NUMBER";
						}
					}
					else // unvalid bank number
					{
						cout << "UNVALID NUMBER";
					}
					break; // case 2 ( add money ) ends here
				case 3:
					cout << "                                                            * ---------E A S Y  L O A D--------- *" << endl << endl;
					cout << endl;
					cout << "CHOOSE SIM" << endl;
					cout << "(1) ZONG" << endl;
					cout << "(2) JAZZ" << endl;
					cout << "(3) UFONE" << endl;
					cout << endl;
					cout << "ENTER SIM NUMBER: ";
					cin >> sim;
					cout << endl;
					if (sim == 1 || sim == 2 || sim == 3)
					{
						cout << "ENTER PHONE NUMBER: +92";
						cin >> phone;
						if (phone.size() == 10)
						{
							cout << "NAME: ";
							cin >> name;
							cout << endl;
							cout << "HOW MUCH LOAD YOU WANT TO SEND: ";
							cin >> load;
							cout << endl;
							if (load > cas)
							{
								cout << "NOT ENOUGH BALANCE";
							}
							else if (load <= cas)
							{
								cout << "BALANCE BEFORE EASYLOAD: " << cas << endl;
								cout << endl;
								cas-= load;
								cout << "BALANCE AFTER EASYLOAD: " << cas;
								cout << endl;
								cout << user_name << " HAS SUCCESSFULLY SENT EASY LOAD OF RS:" << load << " TO " << name << " 0" << phone << "." << endl;

								ofstream easy_load;
								easy_load.open("easy_load.txt", ios::app);
								if (easy_load.is_open())
								{
									easy_load << phone << " " << name << endl;
								}

								ofstream final;
								final.open("final.txt" ,ios::app);
								final << user_name << " HAS SUCCESSFULLY SENT EASY LOAD OF RS:" << load << " TO " << name << " " << phone << "." << endl;
							}
						}
						else // unvalid phone number
						{
							cout << "UNVALID PHONE NUMBER NUMBER";
						}
					}
					else // unvalid sim number
					{
						cout << "UNVALID SIM NUMBER";
					}
					break; // case 3 ( easy-load ) ends here
				case 4:
					cout << "                                                          * ---------B I L L  P A Y M E N T--------- *" << endl << endl;
					cout << endl;
					cout << "CHOOSE AN OPTION" << endl;
					cout << "(1) GAS BILL" << endl;
					cout << "(2) WATER BILL" << endl;
					cout << "(3) ELECTRICAL BILL" << endl;
					cout << endl;
					cout << "ENTER A NUMBER: ";
					cin >> bill;
					cout << endl;
					if (bill == 1 || bill == 2 || bill == 3)
					{
						cout << "ENTER YOUR BILL(10) NUMBER: ";
						cin >> b_number;
						if (b_number.size() == 10)
						{
							id_number(b_number);
							cout << "NAME: ";
							cin >> name;
							cout << "ENTER COMPANY NAME TO WHOM YOU ARE REGISTERED WITH: ";
							cin >> company;
							cout << endl;
							cout << "HOW MUCH BILL DO YOU WANT TO PAY: ";
							cin >> bill_pay;
							cout << endl;
							if (bill_pay > cas)
							{
								cout << "NOT ENOUGH BALANCE";
							}
							else if (bill_pay <= cas)
							{
								cout << "BALANCE BEFORE BILL PAYMENT: " << cas << endl;
								cout << endl;
								cas-= bill_pay;
								cout << "BALANCE AFTER BILL PAYMENT: " << cas;
								cout << endl;
								cout << name << " HAS SUCCESSFULLY PAYED THEIR BILL OF RS:" << bill_pay << " TO " << company << "." << endl;

								ofstream bill_payment;
								bill_payment.open("bill_payment.txt", ios::app);
								if (bill_payment.is_open())
								{
									bill_payment << name << " " << company << endl;
								}

								ofstream final;
								final.open("final.txt",ios::app);
								final << name << " HAS SUCCESSFULLY PAYED THEIR BILL OF RS:" << bill_pay << " TO " << company << "." << endl;
								final.close();
							}
						}
						else // unvalid bill number
						{
							cout << "UNVALID BILL NUMBER";
						}
					}
					else // unvalid option number
					{
						cout << "UNVALID OPTION";
					}
					break; // case 4 ( bill payment ) ends here
				default:
				{
					cout << "UNVALID ENTERY...";
					break;
				}
				}

				cout << endl; cout << endl;
				cout << "TO GO BACK TO THE MAIN MENU PRESS [ 1 ] EITHER PRESS [ 0 ]" << endl << endl;
				cin >> back;
				}
				while(back==1);
				cout << endl;
				cout << "YOUR CURRENT IS: ";
				cout << cas;
				cout << endl;
				cout << endl;
		cout << " T H A N K  Y O U  F O R  C H O O S I N G  U S ";
		cout << endl;				
}
}
else
{
        cout << endl;
		cout << "YOUR CURRENT IS: ";
		cout << cas;
    	cout << endl;
    	cout << endl;
		cout << " T H A N K  Y O U  F O R  C H O O S I N G  U S ";
		cout << endl;
}

		
	
	return 0;
}

//encryption the cradit card
void id_number(string n)
 {
	int temp = 0;
	final.open("final.txt", ios::app);
	final<<"DIGIT CRADIT CARD NUMBER: -->> "<<n<<endl;
	final << "DIGIT CRADIT CARD NUMBER IN ENCRYPTED: -->>  ";
	for (int i = 0; i < n.size(); i++)
	{
		int x = int(n[i]);
		if (x >= 48 && x <= 57)
		{
			x = x + temp;
			if (x > 57)
			{
				x = x - 9;
			}
		}
		char ch = char(x);

		final << ch;

		temp = temp + 1;
	}
	final << endl;
	final.close();
	
 }
 int mask()
{
	char pwd[20], ch;
	
    cout << "                                                                          PIN: ";
	for(int i=0; i<4; ++i)
	{
		ch = getch(); //allows you to press any key without displaying it
		pwd[i] = ch;
		ch = '*';
		cout << ch;
		if(ch==13)
		{	//ascii code for enter key
			cout << "*";
		}
		else if(ch==8)
		{	//ascii code for backspace
			cout << "";
		}
	}
}
