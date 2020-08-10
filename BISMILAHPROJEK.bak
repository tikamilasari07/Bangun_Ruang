#include <stdio.h>
#include <conio.h>
#include <windows.h>
#define phi=3.14
#include <stdlib.h>
#include <math.h>

char nama[100];
char passw[100];
void login();
void b_login();
void bingkai_2();
void menu();
void persegi_panjang();
void persegi();
void segitiga();
void jajargenjang();
void belah_ketupat();
void layang_layang();
void trapesium();
void lingkaran();
void materi_pp();
void materi_p();
void materi_s();
void materi_j();
void materi_b();
void materi_l();
void materi_t();
void materi_li();
void contoh_pp();
void contoh_p();
void contoh_s();
void contoh_j();
void contoh_b();
void contoh_l();
void contoh_t();
void contoh_li();
void latihan_p();
void latihan_pp();
void latihan_s();
void latihan_j();
void latihan_b();
void latihan_l();
void latihan_t();
void latihan_li();
void kotak();
void clear(char t[],int x,int y);
//============================variabel global====================///
int tamp=0;
int tamp2=0;
//==========================proto desain========================//
void desain();
void d_persegi_panjang();
void d_persegi();
void d_segitiga();
void d_jajargenjang();
void d_belahketupat();
void d_layanglayang();
void d_trapesium();
void d_lingkaran();
void bingkai();
void lagi();
void lagi_p();
void lagi_s();
void lagi_j();
void lagi_b();
void lagi_l();
void lagi_t();
void lagi_li();
bool y;
//===================================desain===================================//
void bingkai(){
		for(int x=1;x<=40;x++){
       textcolor(28);
       gotoxy(8,x);cprintf("%c",178);Sleep(10);
       gotoxy(100,x);cprintf("%c",178);Sleep(10);
   }
   for(int a=9;a<=100;a++){
   	 textcolor(28);
       gotoxy(a,1);cprintf("%c",178);Sleep(10);
       gotoxy(a,37);cprintf("%c",178);Sleep(10);
   }
}
void kotak_lat(){
   for(int y=44;y<=88;y++){
   	textcolor(28);
      gotoxy(y,14);cprintf("%c",178);
      gotoxy(y,25);cprintf("%c",178);
   }
   for(int y=14;y<=25;y++){
      gotoxy(44,y);cprintf("%c",178);
      gotoxy(88,y);cprintf("%c",178);
   }
}

void kotak(){
	for(int x=1;x<=35;x++){
        textcolor(28);
        gotoxy(8,x);cprintf("%c",178);
        gotoxy(130,x);cprintf("%c",178);
   }
   for(int a=8;a<=130;a++){
   	textcolor(28);
      gotoxy(a,1);cprintf("%c",178);
      gotoxy(a,35);cprintf("%c",178);
   }
   for(int b=8;b<=130;b++){
   	textcolor(28);
      gotoxy(b,10);cprintf("%c",178);
   }
}
void desain(){
 		for(int x=1;x<=35;x++){
        textcolor(28);
        gotoxy(8,x);cprintf("%c",178);
        gotoxy(131,x);cprintf("%c",178);
      }
   	for(int a=8;a<=130;a++){
   		textcolor(28);
      	gotoxy(a,1);cprintf("%c",178);
      	gotoxy(a,35);cprintf("%c",178);
   	}
   	for(int b=8;b<=130;b++){
   		textcolor(28);
      	gotoxy(b,10);cprintf("%c",178);
   	}
    	for(int c=1;c<=30;c++){
   		textcolor(28);
   		gotoxy(16,3);textcolor(30);cprintf	("  BBBBBB      AA      NN     NN  GGGGGGG  UU   UU  NN     NN  DDDDDD      AA    TTTTTTTT   AA     RRRRRR  ");Sleep(10);
   		gotoxy(16,4);textcolor(30);cprintf	("  BB    B    A  A     NN N   NN  GG       UU   UU  NN N   NN  DD    D    A  A      TT     A  A    RR    R ");Sleep(10);
   		gotoxy(16,5);textcolor(30);cprintf	("  BBBBBB    AAAAAA    NN  N  NN  GG  GGG  UU   UU  NN  N  NN  DD     D  AAAAAA     TT    AAAAAA   RRRRRR ");Sleep(10);
   		gotoxy(16,6);textcolor(30);cprintf	("  BB    B  AA    AA   NN   N NN  GG    G  UU   UU  NN   N NN  DD    D  AA    AA    TT   AA    AA  RR RR   ");Sleep(10);
   		gotoxy(16,7);textcolor(30);cprintf	("  BBBBBB  AA      AA  NN     NN  GGGGGGG  UUUUUUU  NN     NN  DDDDDD  AA      AA   TT  AA      AA RR   RR ");Sleep(10);
   	}
   	for(int c=9;c<40;c++){
      	textcolor(28);
      	gotoxy(c,13);cprintf("%c",178);
   		gotoxy(c,15);cprintf("%c",178);
			gotoxy(c,17);cprintf("%c",178);
			gotoxy(c,19);cprintf("%c",178);
			gotoxy(c,21);cprintf("%c",178);
			gotoxy(c,23);cprintf("%c",178);
			gotoxy(c,25);cprintf("%c",178);
			gotoxy(c,27);cprintf("%c",178);
			gotoxy(c,29);cprintf("%c",178);
			gotoxy(c,33);cprintf("%c",178);
   	}
   	for(int d=11;d<=35;d++){
   		gotoxy(40,d);cprintf("%c",178);
   	}
}


void bingkai_2(){
	for (int x=0;x<30;x++){
   	textcolor(28);
      	gotoxy(4,2+x),cprintf("%c",178);
         gotoxy(120,2+x),cprintf("%c",178);
   }
   for (int y=0;y<30;y++){
   	textcolor(26);
      	gotoxy(6,2+y),cprintf("%c",178);
         gotoxy(118,2+y);cprintf("%c",178);
         gotoxy(2,2+y);cprintf("%c",178);
         gotoxy(122,2+y);cprintf("%c",178);
   }
   for (int x=0;x<119;x++){
   	textcolor(30);
      	gotoxy(3+x,2);cprintf("%c",178);
         gotoxy(3+x,31);cprintf("%c",178);
   }
}

///////////////////////////////// bingkai login ////////////////////////////////
void d_login(){
clrscr();
bingkai_2();

   for(int a=4;a<=25;a++){
   	 //textcolor(3);
       gotoxy(35,5);textcolor(28);cprintf	(" PPPPP  RRRRR    OOOOO    JJJJJJ   EEEEE  kk  k         ");Sleep(10);
       gotoxy(35,6);textcolor(28);cprintf	(" PP   P RR   R  OO   OO       JJ   EE     kk k          ");Sleep(10);
       gotoxy(35,7);textcolor(30);cprintf	(" PPPPP  RRRRR   OO   OO       JJ   EEEEE  kkk           ");Sleep(10);
       gotoxy(35,8);textcolor(30);cprintf	(" PP     RR RR   OO   0O  J    JJ   EE     kk k          ");Sleep(10);
       gotoxy(35,9);textcolor(30);cprintf	(" PP     RR  RR   OOO00    JJJJJJ   EEEEE  kk   k        ");Sleep(10);

       gotoxy(25,11);textcolor(28);cprintf ("BBBBB      AA     HH   HH     AA     SSSSS     AA         CCCCCC  ");Sleep(10);
       gotoxy(25,12);textcolor(28);cprintf ("BB   B    A  A    HH   HH    A  A    SS       A  A        CC      ");Sleep(10);
       gotoxy(25,13);textcolor(30);cprintf ("BBBBB    AAAAAA   HHHHHHH   AAAAAA   SSSSS   AAAAAA       CC      ");Sleep(10);
       gotoxy(25,14);textcolor(30);cprintf ("BB   B  AA    AA  HH   HH  AA    AA     SS  AA    AA      CC      ");Sleep(10);
       gotoxy(25,15);textcolor(30);cprintf ("BBBBB  AA      AA HH   HH AA      AA SSSSS AA      AA     CCCCCC  ");Sleep(10);

   }
   for(int a=43;a<=76;a++){
       textcolor(28);
       gotoxy(a,23);cprintf("%c",178);
       gotoxy(a,26);cprintf("%c",178);
       gotoxy(a,29);cprintf("%c",178);
   }
   for(int y=23;y<=29;y++){
       textcolor(28);
       gotoxy(43,y);cprintf("%c",178);Sleep(10);
       gotoxy(77,y);cprintf("%c",178);Sleep(10);
   }
}

void d_persegi(){
for(int c=1;c<=50;c++){
   	textcolor(28);
   	gotoxy(50,3);textcolor(30);cprintf	("PPPPP  EEEEEE RRRRR   SSSSS  EEEEE  GGGGG  II  ");Sleep(10);
   	gotoxy(50,4);textcolor(30);cprintf	("PP   P EE     RR   R  SS     EE     GG     II  ");
   	gotoxy(50,5);textcolor(30);cprintf	("PPPPP  EEEEE  RRRRR   SSSSS  EEEEE  GG GGG II  ");
   	gotoxy(50,6);textcolor(30);cprintf	("PP     EE     RR R       SS  EE     GG   G II  ");
   	gotoxy(50,7);textcolor(30);cprintf	("PP     EEEEEE RR   R  SSSSS  EEEEE  GGGGGG II  ");
   }
   for(int a=9;a<=40;a++){
   	textcolor(28);
   	gotoxy(a,14);cprintf("%c",178);
   	gotoxy(a,18);cprintf("%c",178);
   	gotoxy(a,22);cprintf("%c",178);
   	gotoxy(a,26);cprintf("%c",178);
   	gotoxy(a,32);cprintf("%c",178);
   }
   for(int d=11;d<=35;d++){
   	textcolor(28);
   	gotoxy(40,d);cprintf("%c",178);
   }
}
void d_persegi_panjang(){
 	for(int c=1;c<=50;c++){
   	textcolor(28);
   	gotoxy(15,3);textcolor(30);cprintf	("PPPPP  EEEEEE RRRRR   SSSSS  EEEEE  GGGGG  II  PPPPP   AAA     NNN   NN JJJJJJJ     AAA     NNN   NN GGGGGG");Sleep(10);
   	gotoxy(15,4);textcolor(30);cprintf	("PP   P EE     RR   R  SS     EE     GG     II  PP   P A   A    NN N  NN      JJ    A   A    NN N  NN GG    ");
   	gotoxy(15,5);textcolor(30);cprintf	("PPPPP  EEEEE  RRRRR   SSSSS  EEEEE  GG GGG II  PPPPP AAAAAAA   NN  N NN      JJ   AAAAAAA   NN  N NN GG GGG");
   	gotoxy(15,6);textcolor(30);cprintf	("PP     EE     RR R       SS  EE     GG   G II  PP   AA     AA  NN   NNN J    JJ  AA     AA  NN   NNN GG   G");
   	gotoxy(15,7);textcolor(30);cprintf	("PP     EEEEEE RR   R  SSSSS  EEEEE  GGGGGG II  PP  AA       AA NN    NN JJJJJJJ AA       AA NN    NN GGGGGG");
   }////////////////////////////////////
   for(int a=9;a<=40;a++){
   	textcolor(28);
   	gotoxy(a,14);cprintf("%c",178);
   	gotoxy(a,18);cprintf("%c",178);
   	gotoxy(a,22);cprintf("%c",178);
   	gotoxy(a,26);cprintf("%c",178);
   	gotoxy(a,32);cprintf("%c",178);
   }
   for(int d=11;d<=35;d++){
   	gotoxy(40,d);cprintf("%c",178);
   }
}


void d_segitiga(){
   for(int c=1;c<=30;c++){
   	textcolor(28);
   	gotoxy(30,3);textcolor(30);cprintf	("                   SSSSS EEEEE GGGGGG  II TTTTTT II GGGGGG     AA       ");Sleep(10);
   	gotoxy(30,4);textcolor(30);cprintf	("                   SS    EE    GG      II   TT   II GG        A  A      ");
   	gotoxy(30,5);textcolor(30);cprintf	("                   SSSSS EEEEE GG GGG  II   TT   II GG GGG   AAAAAA     ");
   	gotoxy(30,6);textcolor(30);cprintf	("                      SS EE    GG   G  II   TT   II GG   G  AA    AA    ");
   	gotoxy(30,7);textcolor(30);cprintf	("                   SSSSS EEEEE GGGGGG  II   TT   II GGGGGG AA      AA   ");
   }
   for(int a=9;a<=40;a++){
   	textcolor(28);
   	gotoxy(a,14);cprintf("%c",178);
   	gotoxy(a,18);cprintf("%c",178);
   	gotoxy(a,22);cprintf("%c",178);
   	gotoxy(a,26);cprintf("%c",178);
   	gotoxy(a,32);cprintf("%c",178);
   }
   for(int d=11;d<=35;d++){
   	gotoxy(40,d);cprintf("%c",178);
   }
}
void d_jajargenjang(){
   for(int c=1;c<=30;c++){
   	textcolor(28);
   	gotoxy(15,3);textcolor(30);cprintf("    JJJJJJ     AA     JJJJJJ     AA     RRRRRR   GGGGGG EEEEE NN    NN JJJJJJ     AA     NN    NN GGGGGG");Sleep(10);
   	gotoxy(15,4);textcolor(30);cprintf("        JJ    A  A        JJ    A  A    RR   RR  GG     EE    NNN   NN     JJ    A  A    NNN   NN GG    ");
   	gotoxy(15,5);textcolor(30);cprintf("        JJ   AAAAAA       JJ   AAAAAA   RRRRRR   GG GGG EEEEE NN N  NN     JJ   AAAAAA   NN N  NN GG GGG");
   	gotoxy(15,6);textcolor(30);cprintf("   J    JJ  AA    AA J    JJ  AA    AA  RR   RR  GG   G EE    NN   NNN J   JJ  AA    AA  NN   NNN GG   G");
   	gotoxy(15,7);textcolor(30);cprintf("    JJJJJJ AA      AA JJJJJJ AA      AA RR    RR GGGGGG EEEEE NN    NN JJJJJJ AA      AA NN    NN GGGGGG");
   }
   for(int a=9;a<=40;a++){
   	textcolor(28);
   	gotoxy(a,14);cprintf("%c",178);
   	gotoxy(a,18);cprintf("%c",178);
   	gotoxy(a,22);cprintf("%c",178);
   	gotoxy(a,26);cprintf("%c",178);
   	gotoxy(a,32);cprintf("%c",178);
   }
   for(int d=11;d<=35;d++){
   	gotoxy(40,d);cprintf("%c",219);
   }
}
void d_belahketupat(){
    for(int c=1;c<=30;c++){
   	textcolor(28);
   	gotoxy(25,3);textcolor(30);cprintf("BBBBB  EEEEE LL         AA     HH   HH   KK  KK EEEEE TTTTTTT UU  UU PPPPP     AA  TTTTTTT");Sleep(10);
   	gotoxy(25,4);textcolor(30);cprintf("BB   B EE    LL        A  A    HH   HH   KK K   EE      TT    UU  UU PP   P   A  A    TT  ");
   	gotoxy(25,5);textcolor(30);cprintf("BBBBB  EEEEE LL       AAAAAA   HHHHHHH   KKK    EEEEE   TT    UU  UU PPPPP   AAAAAA   TT  ");
   	gotoxy(25,6);textcolor(30);cprintf("BB   B EE    LL      AA    AA  HH   HH   KK K   EE      TT    UU  UU PP     AA    AA  TT  ");
   	gotoxy(25,7);textcolor(30);cprintf("BBBBB  EEEEE LLLLLL AA      AA HH   HH   KK  KK EEEEE   TT    UUUUUU PP    AA      AA TT  ");
   }
   for(int a=9;a<=40;a++){
   	textcolor(28);
   	gotoxy(a,14);cprintf("%c",178);
   	gotoxy(a,18);cprintf("%c",178);
   	gotoxy(a,22);cprintf("%c",178);
   	gotoxy(a,26);cprintf("%c",178);
   	gotoxy(a,32);cprintf("%c",178);
   }
   for(int d=11;d<=35;d++){
   	gotoxy(40,d);cprintf("%c",178);
   }
}
void d_layanglayang(){
    for(int c=1;c<=30;c++){
   	textcolor(28);
   	gotoxy(19,3);textcolor(30);cprintf("LL         AA  YY    YY   AA     NN   NN GGGGGGG   LL         AA   YY    YY   AA     NN   NN GGGGGGG      ");Sleep(10);
   	gotoxy(19,4);textcolor(30);cprintf("LL        A  A  YY  YY   A  A    NNN  NN GG        LL        A  A   YY  YY   A  A    NNN  NN GG           ");
   	gotoxy(19,5);textcolor(30);cprintf("LL       AAAAAA  YYYY   AAAAAA   NN N NN GG GGGG   LL       AAAAAA   YYYY   AAAAAA   NN N NN GG GGGG      ");
   	gotoxy(19,6);textcolor(30);cprintf("LL      AA    AA  YY   AA    AA  NN  NNN GG    G   LL      AA    AA   YY   AA    AA  NN  NNN GG    G      ");
   	gotoxy(19,7);textcolor(30);cprintf("LLLLLL AA      AA YY  AA      AA NN   NN GGGGGGG   LLLLLL AA      AA  YY  AA      AA NN   NN GGGGGGG      ");
   }
   for(int a=9;a<=40;a++){
   	textcolor(28);
   	gotoxy(a,14);cprintf("%c",178);
   	gotoxy(a,18);cprintf("%c",178);
   	gotoxy(a,22);cprintf("%c",178);
   	gotoxy(a,26);cprintf("%c",178);
   	gotoxy(a,32);cprintf("%c",178);
   }
   for(int d=11;d<=35;d++){
   	gotoxy(40,d);cprintf("%c",178);
   }
}
void d_trapesium(){
   for(int c=1;c<=30;c++){
   	textcolor(28);
   	gotoxy(35,3);textcolor(30);cprintf	("TTTTTT RRRRR       AA     PPPPP  EEEEE SSSSS II UU  UU MM    MM");Sleep(10);
   	gotoxy(35,4);textcolor(30);cprintf	("  TT   RR   R     A  A    PP   P EE    SS    II UU  UU MMM  MMM");
   	gotoxy(35,5);textcolor(30); cprintf	("  TT   RRRRR     AAAAAA   PPPPP  EEEEE SSSSS II UU  UU MM MM MM");
   	gotoxy(35,6);textcolor(30); cprintf	("  TT   RR  RR   AA    AA  PP     EE       SS II UU  UU MM    MM");
   	gotoxy(35,7);textcolor(30); cprintf	("  TT   RR   RR AA      AA PP     EEEEE SSSSS II UUUUUU MM    MM");
   }
   for(int a=9;a<=40;a++){
   	textcolor(28);
   	gotoxy(a,14);cprintf("%c",178);
   	gotoxy(a,18);cprintf("%c",178);
   	gotoxy(a,22);cprintf("%c",178);
   	gotoxy(a,26);cprintf("%c",178);
   	gotoxy(a,32);cprintf("%c",178);
   }
   for(int d=11;d<=35;d++){
   	gotoxy(40,d);cprintf("%c",178);
   }
}
void d_lingkaran(){
    for(int c=1;c<=30;c++){
   	textcolor(28);
   	gotoxy(35,3);textcolor(30);cprintf	("LL     II NN   NN GGGGGG KK  K     AA     RRRRRR      AA     NN   NN");Sleep(10);
   	gotoxy(35,4);textcolor(30);cprintf	("LL     II NNN  NN GG     KK K     A  A    RR    R    A  A    NNN  NN");
   	gotoxy(35,5);textcolor(30);cprintf	("LL     II NN N NN GG GGG KKK     AAAAAA   RRRRRR    AAAAAA   NN N NN");
   	gotoxy(35,6);textcolor(30);cprintf	("LL     II NN  NNN GG  GG KK K   AA    AA  RR  RR   AA    AA  NN  NNN");
   	gotoxy(35,7);textcolor(30);cprintf	("LLLLLL II NN   NN GGGGGG KK  K AA      AA RR   RR AA      AA NN   NN");
   }
   for(int a=9;a<=40;a++){
   	textcolor(28);
   	gotoxy(a,14);cprintf("%c",178);
   	gotoxy(a,18);cprintf("%c",178);
   	gotoxy(a,22);cprintf("%c",178);
   	gotoxy(a,26);cprintf("%c",178);
   	gotoxy(a,32);cprintf("%c",178);
   }
   for(int d=11;d<=35;d++){
   	gotoxy(40,d);cprintf("%c",178);
   }
}

//================================kotak materi dkk===========================//
void kotak_materi (){
  for(int x=42;x<=88;x++){
  	  textcolor(28);
      gotoxy(x,13);cprintf("%c",219);Sleep(10);
      gotoxy(x,33);cprintf("%c",219);Sleep(10);
  }
  for(int y=13;y<=33;y++){
  	  textcolor(28);
      gotoxy(42,y);cprintf("%c",219);Sleep(10);
      gotoxy(88,y);cprintf("%c",219);Sleep(10);
  }
}
void kotak_contoh(){
	kotak_materi();
   	textcolor(28);
   	for(int c=20;c<=33;c++){
   		gotoxy(60,c);cprintf("%c",219);
   	}
   	for(int d=42;d<=88;d++){
      gotoxy(d,20);cprintf("%c",219);
   	}
}
void pembuka(){
   clrscr();
  	for(int x=1;x<=30;x++){
        textcolor(28);
        gotoxy(8,x);cprintf("%c",178);
        gotoxy(118,x);cprintf("%c",178);
   }
   for(int a=8;a<=118;a++){
   	textcolor(28);
      gotoxy(a,1);cprintf("%c",178);
      gotoxy(a,30);cprintf("%c",178);
   }


   for(int c=1;c<=30;c++){
      textcolor(28);
      gotoxy(10,5);textcolor(28);cprintf ("                                                                                              ||  ");  Sleep(30);
   	gotoxy(10,6);textcolor(28);cprintf ("                                                                                            ||  ||   ");
   	gotoxy(10,7);textcolor(28);cprintf	(" ||||||||||||||||||  |||||||||||    |||          |||||||||||||||      ||||||||||          ||      ||    ");
   	gotoxy(10,8);textcolor(28);cprintf	(" ||              ||  ||       ||   || ||        ||            ||     ||        ||        ||        ||  ");
   	gotoxy(10,9);textcolor(28);cprintf	(" ||              ||  ||       ||  ||   ||      ||            ||     ||          ||      ||          ||  ");
   	gotoxy(10,10);textcolor(28);cprintf (" ||              ||  ||       || ||     ||    ||            ||     ||            ||      ||        ||   ");
   	gotoxy(10,11);textcolor(28);cprintf (" ||||||||||||||||||  ||||||||||||||||||||||  ||||||||||||||||     ||||||||||||||||||      ||      ||    ");
      gotoxy(10,12);textcolor(28);cprintf ("                                                                                           ||   ||  ");
      gotoxy(10,13);textcolor(28);cprintf ("                                                                                             |||   ");

}
	/*for (int a=1;a<=50;a++){
   	textcolor(14);
      Sleep (50); */
		gotoxy(25,17);textcolor(30);cprintf("  APLIKASI RUANG DATAR ");
   	gotoxy(10,18);textcolor(30);cprintf("Selamat datang di aplikasi ruang datar yang didalamnya terdapat pengertian rumus dan contoh soal");
   	gotoxy(10,19);textcolor(30);cprintf("memudahkan anda untuk belajar ruang datar dan memahami apa saja yang termasuk ruang datar ");
   	gotoxy(10,20);textcolor(30);cprintf("setiap ruang datar terdapat pengertian rumus dan soal");
   	gotoxy(10,21);textcolor(30);cprintf("Aplikasi ini dibuat untuk memenuhi tugas akhir pelatihan bahasa pemograman C");
      //gotoxy(a+13,25);textcolor(13);cprintf(" Created By Tika MIlasari ");
   	gotoxy(85,27);textcolor(30);cprintf("TEKAN Y UNTUK LAMJUT :))");
   //}
   char pilih;
	pilih=getch();
	if(pilih=='y'|| pilih=='Y'){
   		clrscr();
   		menu();
	}else{
   		pembuka();
	}
}

void penutup(){
	clrscr();
   for(int x=1;x<=37;x++){
       textcolor(28);
       gotoxy(5,x);cprintf("%c",178);Sleep(10);
       gotoxy(143,x);cprintf("%c",178);Sleep(10);
   }for(int a=5;a<=142;a++){
   	 textcolor(28);
       gotoxy(a,1);cprintf("%c",178);Sleep(10);
       gotoxy(a,37);cprintf("%c",178);Sleep(10);
   }//

	for(int a=5;a<=10;a++){
		gotoxy(a+3,8);textcolor(a);cprintf(" ________________");
   	gotoxy(a+3,9);textcolor(a);cprintf("|                |");
   	gotoxy(a+3,10);textcolor(a);cprintf("| PESEGI PANJANG |");
   	gotoxy(a+3,11);textcolor(a);cprintf("|________________|");
   	Sleep(20);
	}

	for(int b=10;b<=25;b++){
		textcolor(b);
   	gotoxy(b+3,18);cprintf(" _________");
   	gotoxy(b+3,19);cprintf("|         |");
   	gotoxy(b+3,20);cprintf("| PERSEGI |");
   	gotoxy(b+3,21);cprintf("|_________|"); Sleep(20);
	}

	for(int a=10;a<=29;a++){
   	gotoxy(a+3,25);textcolor(a);cprintf(" ______________");
   	gotoxy(a+3,26);textcolor(a);cprintf("|              |");
   	gotoxy(a+3,27);textcolor(a);cprintf("| JAJARGENJANG |");
   	gotoxy(a+3,28);textcolor(a);cprintf("|______________|");
   	Sleep(20);
   }

   for(int a=115;a>=100;a--){
   	gotoxy(a,18);textcolor(a);cprintf(" __________");
   	gotoxy(a,19);textcolor(a);cprintf("|          |");
   	gotoxy(a,20);textcolor(a);cprintf("| SEGITIGA |");
   	gotoxy(a,21);textcolor(a);cprintf("|__________|");
   	Sleep(20);
	}

	for(int a=113;a>=88;a--){
   	textcolor(a);
   	gotoxy(a,25);cprintf(" _______________");
   	gotoxy(a,26);cprintf("|               |");
   	gotoxy(a,27);cprintf("| BELAH KETUPAT |");
   	gotoxy(a,28);cprintf("|_______________|");
		Sleep(20);
	}

	for(int a=121;a>=104;a--){
   	textcolor(a);
   	gotoxy(a,8);cprintf(" ___________");
   	gotoxy(a,9);cprintf("|           |");
   	gotoxy(a,10);cprintf("| LINGKARAN |");
   	gotoxy(a,11);cprintf("|___________|");
   	Sleep(20);
	}

	for(int a=1;a<=50;a++){
 		gotoxy(25,12);textcolor(30);cprintf("OOOOO0 OOOO0 OOOOOO  OO OO     00     000      00   00     000     OOOOO 00 00   00 ");
		gotoxy(25,13);textcolor(30);cprintf("  00   OO    OO   O  OO OO00 0000    00 00     00  00     00 00    OO    00 00   00 ");
		gotoxy(25,14);textcolor(30);cprintf("  OO   OOOOO OO0000  OO OO  0  00   00   00    0000      00   00   OO000 00 0000000 ");
		gotoxy(25,15);textcolor(30);cprintf("  OO   OO    OO  00  OO OO     00  000000000   00  00   000000000     00 00 00   00 ");
		gotoxy(25,16);textcolor(30);cprintf("  OO   OO0OO OO   00 OO OO     00 00       00  00   00 00       00 OOOOO 00 00   00 ");
		//gotoxy(20,16);textcolor(a);cprintf("  OO");
      Sleep(20);
	}

   for (int a=1;a<=50;a++){
   	textcolor(28);
      Sleep (50);
      gotoxy (a+5,34);textcolor(30);cprintf(" Created By Tika Milasari ");
	}

   for (int a=1;a<=50;a++){
   	textcolor(28);
      Sleep (50);
      gotoxy (a+5,36);textcolor(30);cprintf(" D3 Manajemen Informatika 15");
	   gotoxy(32,42);
   }
}


void hapus_p(){
		gotoxy(64,16);printf("               ");
}
void hapus_pp(){
   	 gotoxy(46,26);printf("                                          ");
       gotoxy(46,27);printf("                                          ");
       gotoxy(46,28);printf("                                          ");
       gotoxy(46,29);printf("                                          ");
       gotoxy(46,30);printf("                                          ");
       gotoxy(46,31);printf("                                          ");
}
void hapus_s(){
		gotoxy(47,23);printf("                            ");
		gotoxy(47,24);printf("                            ");
		gotoxy(47,25);printf("                                  ");
}
void hapus_j(){
		gotoxy(48,22);printf("                               ");
		gotoxy(48,23);printf("                               ");
		gotoxy(48,24);printf("     	                          ");

}
void hapus_b(){
		gotoxy(48,14);printf("                               ");
		gotoxy(48,16);printf("                               ");
		gotoxy(48,18);printf("                                  ");

}
void hapus_l(){
		gotoxy(48,21);printf("                                      ");
		gotoxy(48,22);printf("                                     ");
		gotoxy(48,23);printf("                                    ");
		gotoxy(48,24);printf("                                    ");

}
void hapus_t(){
	gotoxy(48,15);printf("                                  ");
	gotoxy(48,16);printf("                                  ");
	gotoxy(48,17);printf("                                  ");
	gotoxy(48,18);printf("                                  ");
}
void hapus_li(){
	gotoxy(48,14);printf("                               ");
	gotoxy(48,16);printf("                               ");
	gotoxy(48,18);printf("                               ");

}
void hapus(){
         gotoxy(44,24);printf("                ");
			gotoxy(44,25);printf("                ");
			gotoxy(44,28);printf("               ");
			gotoxy(44,29);printf("               ");
			gotoxy(61,21);printf("                          ");
			gotoxy(61,23);printf("                          ");
			gotoxy(61,24);printf("                          ");
			gotoxy(61,25);printf("                          ");
			gotoxy(61,26);printf("                          ");
			gotoxy(61,27);printf("                          ");
			gotoxy(61,28);printf("                          ");
			gotoxy(61,29);printf("                          ");
			gotoxy(61,30);printf("                          ");
			gotoxy(61,31);printf("                          ");
			gotoxy(61,32);printf("                          ");
}

//=================================== mulai===================================//
void awal(){
	kotak();
}
void login(){
	d_login();
	gotoxy(45,25);textcolor(30);cprintf("Username    :");
	gotoxy(63,25);gets(nama);
	gotoxy(45,28);textcolor(30);cprintf("Password  :");
	gotoxy(63,28);gets(passw);
	if(strcmp(nama,"mila")==0 && strcmp(passw,"2105")==0){
         for(int s=35;s<=69;s++){
         	textcolor(30);
         	gotoxy(s,33);cprintf("%c",219);Sleep(100);
         }
   		clrscr();
   		pembuka();
	}else{
      	clrscr();
		login();
	}
}
void menu(){
	char pilih;
	desain();
	gotoxy(10,12);textcolor(30);cprintf("       MENU");
	gotoxy(10,14);textcolor(30);cprintf("1.PERSEGI PANJANG");         gotoxy(45,14);textcolor(28);cprintf ("  |||||||||||    |||          |||||||||||||||    ||||||||||    ||||||||||||||||||");   Sleep(10);
	gotoxy(10,16);textcolor(30);cprintf("2.PERSEGI ");                gotoxy(45,15);textcolor(28);cprintf ("  ||       ||   || ||        ||            ||   ||        ||   ||              ||");
	gotoxy(10,18);textcolor(30);cprintf("3.SEGITIGA");                gotoxy(45,16);textcolor(28);cprintf ("  ||       ||  ||   ||      ||            ||   ||          ||  ||              ||");
	gotoxy(10,20);textcolor(30);cprintf("4.JAJARGENJANG");            gotoxy(45,17);textcolor(28);cprintf ("  ||       || ||     ||    ||            ||   ||            || ||              ||");
	gotoxy(10,22);textcolor(30);cprintf("5.BELAH KETUPAT");           gotoxy(45,18);textcolor(28);cprintf ("  ||||||||||||||||||||||  ||||||||||||||||   ||||||||||||||||||||||||||||||||||||");
	gotoxy(10,24);textcolor(30);cprintf("6.LAYANG-LAYANG");           gotoxy(45,20);textcolor(30);cprintf("   BANGUN DATAR");
	gotoxy(10,26);textcolor(30);cprintf("7.TRAPESIUM");               gotoxy(45,21);textcolor(30);cprintf("Bangun-bangun geometri baik dalam kelompok bangun datar maupun bangun ruang merupakan");
	gotoxy(10,28);textcolor(30);cprintf("8.LINGKARAN");               gotoxy(45,22);textcolor(30);cprintf("sebuah konsep abstrakArtinya bangun-bangun tersebut bukan merupakan sebuah benda");
	gotoxy(10,30);textcolor(30); cprintf("9.KELUAR");                 gotoxy(45,23);textcolor(30);cprintf("konkret yg dapat dilihat maupun dipegang.Demikian pula dengan konsep bangun geometri");
                                                                     gotoxy(45,24);textcolor(30);cprintf("bangun-bangun tersebut merupakan suatu sifat.sedangkan yang konkret,yang biasadilihat");
                                                                     gotoxy(45,25);textcolor(30);cprintf("maupun dipegang, adalah benda-benda yang memiliki sifat bangun geometri. Misalnya");
                                                                     gotoxy(45,26);textcolor(30);cprintf("persegi panjang,konseppersegi panjang merupakan sebuah konsep abstrak yang");
   																						gotoxy(45,27);textcolor(30);cprintf("diidentifiaksikan melalui sebuah karakteristik. Dari uraiandi atas maka bangun");
                                                                     gotoxy(45,28);textcolor(30);cprintf("datar dapat didefinisikan sebagai bangun yang rata yang mempunyai dua dimensi ");
                                                                     gotoxy(45,29);textcolor(30);cprintf("yaitu panjang dan lebar tetapi tidak mempunyai tinggi dan tebal. Dengan ");
                                                                     gotoxy(45,30);textcolor(30);cprintf("demikian pengertian bangun datar adalah abstrak.");
                                                                     gotoxy(10,34);textcolor(30);cprintf("Masukkan Pilihan anda :");
	pilih=getch();
   if(pilih=='1'){
			clrscr();
   		persegi_panjang();
	}else if(pilih=='2'){
			clrscr();
   		persegi();
	}else if(pilih=='3'){
			clrscr();
   		segitiga();
   }else if(pilih=='4'){
			clrscr();
   		jajargenjang();
	}else if(pilih=='5'){
			clrscr();
   		belah_ketupat();
	}else if(pilih=='6'){
			clrscr();
   		layang_layang();
	}else if(pilih=='7'){
			clrscr();
   		trapesium();
	}else if(pilih=='8'){
			clrscr();
   		lingkaran();
	}else if(pilih=='9'){
			clrscr();
   		penutup();
	}else{
  		menu();

	}
}

void persegi_panjang(){
	char pilih;
	kotak();
	d_persegi_panjang();
   textcolor(28);
	gotoxy(10,12);textcolor(30);cprintf("1.Materi\n");
	gotoxy(10,16);textcolor(30);cprintf("2.Contoh Soal\n");
	gotoxy(10,20);textcolor(30);cprintf("3.Latihan Soal\n");
	gotoxy(10,24);textcolor(30);cprintf("4.Kembali\n");
	gotoxy(10,33);textcolor(30);cprintf("Masukkan Pilihan Anda :");
	pilih=getch();
	if(pilih=='1'){
			materi_pp();
	}else if (pilih=='2'){
   		contoh_pp();
	}else if (pilih=='3'){
   		clrscr();
   		latihan_pp();
	}else if (pilih=='4'){
   		clrscr();
   		menu();
	}else{
   		persegi_panjang();
	}
}
void persegi(){
	char pilih;
	kotak();
	d_persegi();
   textcolor(14);
	gotoxy(10,12);textcolor(30);cprintf("1.Materi\n");
	gotoxy(10,16);textcolor(30);cprintf("2.Contoh Soal\n");
	gotoxy(10,20);textcolor(30);cprintf("3.Latihan Soal\n");
	gotoxy(10,24);textcolor(30);cprintf("4.Kembali\n");
	gotoxy(10,33);textcolor(30);cprintf("Masukkan Pilihan Anda :");
	pilih=getch();
	if(pilih=='1'){
     	materi_p();
	}else if (pilih=='2'){
	   	contoh_p();
	}else if (pilih=='3'){
   		clrscr();
   		latihan_p();
	}else if (pilih=='4'){
   		clrscr();
   		menu();
	}else{
   		persegi();
	}
}

void segitiga(){
	char pilih;
	kotak();
	d_segitiga();
   textcolor(14);
	gotoxy(10,12);textcolor(30);cprintf("1.Materi\n");
	gotoxy(10,16);textcolor(30);cprintf("2.Contoh Soal\n");
	gotoxy(10,20);textcolor(30);cprintf("3.Latihan Soal\n");
	gotoxy(10,24);textcolor(30);cprintf("4.Kembali\n");
	gotoxy(10,33);textcolor(30);cprintf("Masukkan Pilihan Anda :");
	pilih=getch();
	if(pilih=='1'){
		materi_s();
	}else if (pilih=='2'){
   		contoh_s();
	}else if (pilih=='3'){
   		clrscr();
   		latihan_s();
	}else if (pilih=='4'){
   		clrscr();
  	 		menu();
	}else{
   		segitiga();
	}
}
void jajargenjang(){
	char pilih;
	kotak();
	d_jajargenjang();
   textcolor(14);
	gotoxy(10,12);textcolor(30);cprintf("1.Materi\n");
	gotoxy(10,16);textcolor(30);cprintf("2.Contoh Soal\n");
	gotoxy(10,20);textcolor(30);cprintf("3.Latihan Soal\n");
	gotoxy(10,24);textcolor(30);cprintf("4.Kembali\n");
	gotoxy(10,33);textcolor(30);cprintf("Masukkan Pilihan Anda :");
	pilih=getch();
	if(pilih=='1'){
			materi_j();
	}else if (pilih=='2'){
     		contoh_j();
	}else if (pilih=='3'){
   		clrscr();
   		latihan_j();
	}else if (pilih=='4'){
   		clrscr();
   		menu();
	}else{
   		jajargenjang();
	}
}
void belah_ketupat(){
	kotak();
	d_belahketupat();
	char pilih;
   textcolor(14);
	gotoxy(10,12);textcolor(30);cprintf("1.Materi\n");
	gotoxy(10,16);textcolor(30);cprintf("2.Contoh Soal\n");
	gotoxy(10,20);textcolor(30);cprintf("3.Latihan Soal\n");
	gotoxy(10,24);textcolor(30);cprintf("4.Kembali\n");
	gotoxy(10,33);textcolor(30);cprintf("Masukkan Pilihan Anda :");
	pilih=getch();
	if(pilih=='1'){
			materi_b();
	}else if (pilih=='2'){
   		contoh_b();
	}else if (pilih=='3'){
   		clrscr();
   		latihan_b();
	}else if (pilih=='4'){
   		clrscr();
   		menu();
	}else{
   		belah_ketupat();
	}
}
void layang_layang(){
	char pilih;
	kotak();
	d_layanglayang();
   textcolor(14);
	gotoxy(10,12);textcolor(30);cprintf("1.Materi\n");
	gotoxy(10,16);textcolor(30);cprintf("2.Contoh Soal\n");
	gotoxy(10,20);textcolor(30);cprintf("3.Latihan Soal\n");
	gotoxy(10,24);textcolor(30);cprintf("4.Kembali\n");
	gotoxy(10,33);textcolor(30);cprintf("Masukkan Pilihan Anda :");
	pilih=getch();
	if(pilih=='1'){
			materi_l();
	}else if (pilih=='2'){
   		contoh_l();
	}else if (pilih=='3'){
   		clrscr();
    		latihan_l();
	}else if (pilih=='4'){
   		clrscr();
   		menu();
	}else{
   		layang_layang();
	}
}
void trapesium(){
	char pilih;
	kotak();
	d_trapesium();
   textcolor(14);
	gotoxy(10,12);textcolor(30);cprintf("1.Materi\n");
	gotoxy(10,16);textcolor(30);cprintf("2.Contoh Soal\n");
	gotoxy(10,20);textcolor(30);cprintf("3.Latihan Soal\n");
	gotoxy(10,24);textcolor(30);cprintf("4.Kembali\n");
	gotoxy(10,33);textcolor(30);cprintf("Masukkan Pilihan Anda :");
	pilih=getch();
	if(pilih=='1'){
			materi_t();
	}else if (pilih=='2'){
 	   	contoh_t();
	}else if (pilih=='3'){
   		clrscr();
   		latihan_t();
	}else if (pilih=='4'){
   		clrscr();
   		menu();
	}else{
   		trapesium();
	}
}
void lingkaran(){
   kotak();
   d_lingkaran();
	char pilih;
   textcolor(14);
	gotoxy(10,12);textcolor(30);cprintf("1.Materi\n");
	gotoxy(10,16);textcolor(30);cprintf("2.Contoh Soal\n");
	gotoxy(10,20);textcolor(30);cprintf("3.Latihan Soal\n");
	gotoxy(10,24);textcolor(30);cprintf("4.Kembali\n");
	gotoxy(10,33);textcolor(30);cprintf("Masukkan Pilihan Anda :");
	pilih=getch();
	if(pilih=='1'){
			materi_li();
	}else if (pilih=='2'){
   		contoh_li();
	}else if (pilih=='3'){
   		clrscr();
   		latihan_li();
	}else if (pilih=='4'){
   		clrscr();
   		menu();
	}else{
   		lingkaran();
	}
}

void materi_pp(){
	gotoxy(46,14);textcolor(30);cprintf("SIFAT - SIFAT PERSEGI PANJANG");
	gotoxy(46,15);textcolor(30);cprintf("-Memiliki empat sisi serta empat titik sudut");
	gotoxy(46,16);textcolor(30);cprintf("-Memiliki dua pasang sisi sejajar yang ");
   gotoxy(46,17);textcolor(30);cprintf("  berhadapan dan sama panjang");
	gotoxy(46,18);textcolor(30);cprintf("-Keempat sudutnya sama besar yaitu 90°(sudut siku-siku)"); textcolor(14);
	gotoxy(46,19);textcolor(30);cprintf("-Memiliki dua diagonal yang sama panjang ");  gotoxy(90,21);textcolor(30);cprintf("||||||||||||||||||");
	gotoxy(46,20);textcolor(30);cprintf("-Memiliki dua buah simetri lipat");           gotoxy(90,22);textcolor(30);cprintf("||              ||");
	gotoxy(46,21);textcolor(30);cprintf("-Memiliki dua simetri putar");                gotoxy(90,23);textcolor(30);cprintf("||              ||");
                                                                                      gotoxy(90,24);textcolor(30);cprintf("||              ||");
	gotoxy(46,23);textcolor(30);cprintf("RUMUS LUAS PERSEGI PANJANG ");                gotoxy(90,25);textcolor(30);cprintf("||||||||||||||||||");
  	gotoxy(46,24);textcolor(30);cprintf("Luas = Panjang x Lebar");
	gotoxy(46,25);textcolor(30);cprintf("Rumus keliling persegi panjang ");
	gotoxy(46,26);textcolor(30);cprintf("Keliling = 2 x ( Panjang + Lebar )");
	gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
	char pilih;
	pilih=getch();
	if (pilih=='9'){
   		clrscr();
   		persegi_panjang();
	}else{
   		materi_pp();
	}
}
void materi_p(){
	gotoxy(46,14);textcolor(30);cprintf(" SIFAT - SIFAT PERSEGI");
	gotoxy(46,15);textcolor(30);cprintf("-Semua sifat persegi panjang merupakan sifat persegi");
   gotoxy(46,16);textcolor(30);cprintf("-Suatu persegi dapat menempati bingkainya dengan delapan cara.");
	gotoxy(46,17);textcolor(30);cprintf("-Semua sisi persegi adalah sama panjang.");
	gotoxy(46,18);textcolor(30);cprintf("-Memiliki dua pasang sisi yang sejajar dan sama panjang");
  	gotoxy(46,19);textcolor(30);cprintf("-Sudut-sudut suatu persegi dibagi dua sama besar oleh diagonal- diagonalnya");
	gotoxy(46,20);textcolor(30);cprintf("-Diagonal-diagonal persegi saling berpotongan sama panjang membentuk sudut siku-siku\n");
   					                                                                             gotoxy(93,23);textcolor(30);cprintf("|||||||||||||");
	gotoxy(46,22);textcolor(30);cprintf("     RUMUS PERSEGI\n"); 					  	              gotoxy(93,24);textcolor(30);cprintf("||         ||");
	gotoxy(46,23);textcolor(30);cprintf("L = s² atau Luas Persegi = sisi x sisi");				  gotoxy(93,25);textcolor(30);cprintf("||         ||");
   gotoxy(46,23);textcolor(30);cprintf("Dimana L adalah luas S adalah sisi persegi");          gotoxy(93,26);textcolor(30);cprintf("||         ||");
   gotoxy(46,24);textcolor(30);cprintf("K = 4.S atau Keliling Persegi = 4 x Sisi");            gotoxy(93,27);textcolor(30);cprintf("|||||||||||||");
   gotoxy(46,24);textcolor(30);cprintf("Dimana K adalah Keliling S adalah ukuran Sisi");
   gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
	char pilih;
	pilih=getch();
	if(pilih=='9'){
   		clrscr();
   		persegi();
	}else{
   		materi_p();
	}
}

void materi_s(){
	gotoxy(46,14);textcolor(30);cprintf("      SIFAT - SIFAT SEGITIGA");
	gotoxy(46,15);textcolor(30);cprintf("-jumlah panjang dua sisi selalu lebih besar daripada panjang sisi segitiga ");
	gotoxy(46,16);textcolor(30);cprintf("-jumlah sudut-sudut sebuah segitiga adalah 180 deraja");
	gotoxy(46,17);textcolor(30);cprintf("-sisi atau rusuk dan sudut, sifat yang");
	gotoxy(46,18);textcolor(30);cprintf("-sudut terbesar adalah sudut yang menghadap sisi terpanjang");
  	gotoxy(46,19);textcolor(30);cprintf("-sedangkan sudut terkecil adalah sudut yang menghadap sisi terpendek");
	gotoxy(46,20);textcolor(30);cprintf("-besar sudut luar sama dengan jumlah dua sudut yang tidak");
   gotoxy(46,21);textcolor(30);cprintf(" berpenglurus dengan sudut luar tersebut");
   gotoxy(46,23);textcolor(30);cprintf("      JENIS - JESNIS SEGITIGA");
	gotoxy(46,23);textcolor(30);cprintf("-Segitiga Sama Kaki(jika ketiga sisi segitiga sama panjang)");
	gotoxy(46,24);textcolor(30);cprintf("-Segitiga Sama Sisi(jika dua di antara sisi segitiga itu sama panjang)");
	gotoxy(46,25);textcolor(30);cprintf("-Segitiga Sembarang(jika ketiga sisi segitiga tidak sama)");
   gotoxy(46,26);textcolor(30);cprintf("-Segitiga Lancip(jika besar setiap sudut segitiga kurang dari 90 derajat)");
   gotoxy(46,27);textcolor(30);cprintf("-Segitiga Siku-siku(jika salah satu sudut & segitiga besarnya sama dgn 90 derajat");
   gotoxy(46,28);textcolor(30);cprintf("-Segitiga Tumpul(jika salah satu sudut segitiga besarnya lebih besar dari 90 derajat");
	gotoxy(46,29);textcolor(30);cprintf("       RUMUS SEGITIGA");
	gotoxy(46,30);textcolor(30);cprintf("Keliling = Sisi x Sisi x Sisi");
	gotoxy(46,31);textcolor(30);cprintf("Luas = 1/2 x Alas x Tinggi");
	gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
	char pilih;
	pilih=getch();
	if (pilih=='9'){
   		clrscr();
   		segitiga();
	}else{
   		materi_s();
	}
}

void materi_j(){
	gotoxy(46,14);textcolor(30);cprintf("SIFAT - SIFAT JAJARGENJANG");
  	gotoxy(46,15);textcolor(30);cprintf("-Sisi-sisi yang berhadapan di setiap bangun jajar genjang");
   gotoxy(46,17);textcolor(30);cprintf(" selalu sama panjangnya serta sejajar");
  	gotoxy(46,16);textcolor(30);cprintf("-Sudut-sudut yang berhadapan di setiap bangun jajar genjang sama besarnya");
  	gotoxy(46,18);textcolor(30);cprintf("-Jumlah dua besar sudut yang berdekatan di setiap bangun");
   gotoxy(46,19);textcolor(30);cprintf(" jajar genjang adalah 180 derajat");
  	gotoxy(46,20);textcolor(30);cprintf("-Disetiap bangun jajargenjang kedua diagonal yang saling membagi 2 sama panjangnya");
  	gotoxy(46,21);textcolor(30);cprintf("-Memiliki simetri putar tingkat dua dan tidak mempunyai simetri lipat");
  	gotoxy(46,22);textcolor(30);cprintf("-Memiliki dua buah sudut tumpul dan dua buah sudut lancip");
  	gotoxy(46,23);textcolor(30);cprintf("-Jumlah semua sudut yang di miliki jajaran genjang adalah 360 derajat");
  	gotoxy(46,24);textcolor(30);cprintf("RUMUS JANJAR GENJANG");
  	gotoxy(46,25);textcolor(30);cprintf("Luas = Alas x tinggi");
  	gotoxy(46,26);textcolor(30);cprintf("Keliling = 2 x Alas + 2 x Sisi Miring");
  	gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
	char pilih;
	pilih=getch();
	if (pilih=='9'){
   		clrscr();
   		jajargenjang();
	}else{
   		materi_j();
	}
}
void materi_b(){
	gotoxy(46,14);textcolor(30);cprintf("SIFAT - SIFAT BELAH KETUPAT");
	gotoxy(46,15);textcolor(30);cprintf("-Semua sisi-sisinya sama panjang");
	gotoxy(46,16);textcolor(30);cprintf("-Sudut-sudut yang berhadapan besarnya sama dan dibagi");
   gotoxy(46,17);textcolor(30);cprintf(" dua sama besar oleh diagonal-diagonalnya");
	gotoxy(46,18);textcolor(30);cprintf("-Kedua diagonalnya saling membagi dua sama panjang");
   gotoxy(46,19);textcolor(30);cprintf(" dan saling tegak lurus satu sama lainnya");
	gotoxy(46,20);textcolor(30);cprintf("-Mempunyai dua sumbu simetri");
	gotoxy(46,21);textcolor(30);cprintf("-Kedua diagonalnya merupakan sumbu simetri dari bangun belah ketupat");
	gotoxy(46,22);textcolor(30);cprintf("-Memiliki dua simetri lipat");
	gotoxy(46,23);textcolor(30);cprintf("-Memiliki dua simetri putar");
	gotoxy(46,24);textcolor(30);cprintf("-umlah semua sudutnya besarnya adalah 360°");
	gotoxy(46,26);textcolor(30);cprintf("RUMUS BELAH KETUPAT");
	gotoxy(46,27);textcolor(30);cprintf("Luas = 1/2 x d1 x d2");
	gotoxy(46,28);textcolor(30);cprintf("Keliling = 4.s\n");
	gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
	char pilih;
	pilih=getch();
	if (pilih=='9'){
   		clrscr();
   		belah_ketupat();
	}else{
  		materi_b();
	}
}
void materi_l(){
	gotoxy(46,14);textcolor(30);cprintf("SIFAT - SIFAT LAYANG LAYANG");
	gotoxy(46,15);textcolor(30);cprintf("-Terdapatnya dua pasang sisi yang sama panjang");
	gotoxy(46,16);textcolor(30);cprintf("-Terdapatnya sepasang sudut berhadapan yang sama besar");
	gotoxy(46,17);textcolor(30);cprintf("-Terdapatnya satu sumbu simetri yang merupakan diagonal terpanjang");
	gotoxy(46,18);textcolor(30);cprintf("-Salah 1 dari diagonalnya membagi 2 sama panjang diagonal lainnya secara tegak lurus");
	gotoxy(46,19);textcolor(30);cprintf("-Diagonal-diagonal yang dimiliki oleh bangun layang-layang saling tegak lurus");
	gotoxy(46,20);textcolor(30);cprintf("-Diagonal yang menghubungkan sudut puncak membagi dua bagian sudut-sudut puncak");
   gotoxy(46,21);textcolor(30);cprintf(" dan layang-layang menjadi dua buah bagian yang besarnya sama");
	gotoxy(46,23);textcolor(30);cprintf("RUMUS LAYANG - LAYANG");
	gotoxy(46,24);textcolor(30);cprintf("Luas = 1/2 x d1 x d2");
	gotoxy(46,25);textcolor(30);cprintf("Keliling = 2 x s1 + 2 x s2");
	gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
	char pilih;
	pilih=getch();
	if (pilih=='9'){
   		clrscr();
   		layang_layang();
	}else{
   		materi_l();
	}
}
void materi_t(){
	gotoxy(46,14);textcolor(30);cprintf("SIFAT - SIFAT TRAPESIUM");
	gotoxy(46,15);textcolor(30);cprintf("-Jumlah sudut yang berdekatan diantara dua garis sejajar adalah 180°");
	gotoxy(46,16);textcolor(30);cprintf("-Pada trapesium sama kaki,terdapat 2 buah sudut yang berdekatan yang besarnya sama");
	gotoxy(46,17);textcolor(30);cprintf("-Pada trapesium sama kaki,terdapat diagonal yang panjangnya sama");
	gotoxy(46,18);textcolor(30);cprintf("-Pada trapesium sama kaki memiliki satu buah sumbu simetri");
	gotoxy(46,19);textcolor(30);cprintf("-Pada trapesium siku-siku memiliki dua buah sudut siku-siku");
	gotoxy(46,20);textcolor(30);cprintf("-Jumlah semua sudut pada trapesium adalah 360 derajat");
	gotoxy(46,21);textcolor(30);cprintf("-Mempunyai satu buah simetri");
	gotoxy(46,23);textcolor(30);cprintf("JENIS - JENIS TRAPESIUM");
	gotoxy(46,24);textcolor(30);cprintf("1.Trapesium Sembarang");
	gotoxy(46,25);textcolor(30);cprintf("2.Trapesium Sama Kaki");
	gotoxy(46,26);textcolor(30);cprintf("3.Trapesium Siku - Siku");
	gotoxy(46,28);textcolor(30);cprintf("RUMUS TRAPESIUM");
	gotoxy(46,29);textcolor(30);cprintf("Luas = 1/2 x jumlah sisi sejajar x tinggi");
	gotoxy(46,30);textcolor(30);cprintf("Keliling = Jumlah seluruh sisi");
	gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
	char pilih;
	pilih=getch();
	if (pilih=='9'){
   		clrscr();
   		trapesium();
	}else{
   		materi_t();
	}
}
void materi_li(){
	gotoxy(46,14);textcolor(30);cprintf("SIFAT - SIFAT LINGKARAN");
	gotoxy(46,15);textcolor(30);cprintf("-Bidang dalam jarak tertentu yang disebut");
	gotoxy(46,16);textcolor(30);cprintf("-Dengan jari-jari dari seatu titik yang");
	gotoxy(46,17);textcolor(30);cprintf(" disebut dengan pusat");
	gotoxy(46,18);textcolor(30);cprintf("-Mempunyai simetri putar tak terhingga");
	gotoxy(46,19);textcolor(30);cprintf("-Mempunyai simetri lipat serta sumbu yang");
	gotoxy(46,20);textcolor(30);cprintf(" tak terhingga");
	gotoxy(46,21);textcolor(30);cprintf("-Tidak memiliki titik sudut.");
	gotoxy(46,22);textcolor(30);cprintf("-Memiliki satu sisi.");
	gotoxy(46,24);textcolor(30);cprintf("RUMUS LINGKARAN");
	gotoxy(46,25);textcolor(30);cprintf("Luas = phi x r x r");
	gotoxy(46,26);textcolor(30);cprintf("Keliling = phi x d");
	gotoxy(46,27);textcolor(30);cprintf("Keterangan:");
	gotoxy(46,28);textcolor(30);cprintf("phi = 3,14 atau 22/7");
	gotoxy(46,29);textcolor(30);cprintf("r = jari-jari");
	gotoxy(46,30);textcolor(30);cprintf("d = diameter (2 x r)");
	gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
	char pilih;
	pilih=getch();
	if (pilih=='9'){
   			clrscr();
   			lingkaran();
   	}else{
   			materi_li();
	}
}

void contoh_pp(){
	char panjang [10];
	char lebar[10];
   gotoxy(46,14);textcolor(30);cprintf("CONTOH SOAL");
   gotoxy(46,15);textcolor(30);cprintf("1.Sebuah Persegi Panjang memiliki panjang 8 cm dan lebar 5");
   gotoxy(46,16);textcolor(30);cprintf("maka luas dan keliling Persegi Panjang tersebut adalah :");
   gotoxy(46,17);textcolor(30);cprintf("a. 40 cm2 dan 26 cm");
   gotoxy(46,18);textcolor(30);cprintf("b. 40 cm2 dan 40 cm");
   gotoxy(46,19);textcolor(30);cprintf("c. 40 cm2 dan 13 cm");
   gotoxy(46,20);textcolor(30);cprintf("d. 13 cm2 dan 26 cm");
   gotoxy(46,21);textcolor(30);cprintf("Pembahasan");
   gotoxy(46,22);textcolor(30);cprintf("Diketahui ");
   gotoxy(46,23);textcolor(30);cprintf("P = 8 cm");
   gotoxy(46,24);textcolor(30);cprintf("L = 5 cm");
   gotoxy(46,25);textcolor(30);cprintf("Luas = 8 x 5 = 40 cm2");
	gotoxy(46,26);textcolor(30);cprintf("Masukkan Panjang :");gets(panjang);
   if(strlen(panjang)==0)contoh_pp();
	 for(int a=0;a<strlen(panjang);a++){
   	if((panjang[a]>='0'&& panjang [a]<='9')&&(panjang[0]!='0')){
      	continue;
      }else{
         gotoxy(46,27);textcolor(30);cprintf("inputan harus bilangan bulat");Sleep(1000);
         clear(panjang,64,26);
         gotoxy(46,27);printf("                                                      ");
         contoh_pp();
      }
    }
    gotoxy(46,28);textcolor(30);cprintf("Masukkan Lebar :");gets(lebar);
     bool y=true;
     int z=0;
     while(y==true){
      z=0;
      if(strlen(lebar)==0)z=1;
    	 for(int a=0;a<strlen(lebar);a++){
   			if((lebar[a]>='0'&& lebar [a]<='9')&&(lebar[0]!='0')){
               z++;
      		}else{
            	gotoxy(46,29);textcolor(30);cprintf("inputan harus bilangan bulat"); getch();
               clear(lebar,62,28);
            	gotoxy(46,29);printf("                                                     ");
               gotoxy(46,28);textcolor(30);cprintf("Masukkan Lebar :");gets(lebar);
               break;
     		 	}
     		}
         if(z==strlen(lebar) && z!=0){
         	y=false;
         }
         /*else{
         	gotoxy(46,28);textcolor(30);cprintf("Masukkan Lebar :");gets(lebar);
         }*/
     }
	int keliling;
	int luas;
	gotoxy(46,29);textcolor(30);cprintf("Keliling = 2(P + L)");getch();
	keliling=2*(atoi(panjang)+atoi(lebar));
	gotoxy(46,30);textcolor(30);cprintf("Keliling = %d\n",keliling);getch();
	gotoxy(46,31);textcolor(30);cprintf("Luas = P x L");getch();
	luas = (atoi(panjang)*atoi(lebar));
	gotoxy(46,32);textcolor(30);cprintf("Luas = %d",luas);getch();
   gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
	char pilih;
	pilih=getch();
   while(pilih!='9')pilih=getch();
	if (pilih=='9'){
   		clrscr();
 			persegi_panjang();
	}
}

void contoh_p(){
	char sisi[10];
	gotoxy(46,14);textcolor(30);cprintf("CONTOH SOAL");
   gotoxy(46,15);textcolor(30);cprintf("Sebuah poster memiliki bentuk persegi serta mempunai panjang sisi 20 m");
   gotoxy(46,16);textcolor(30);cprintf(" hitunglah Luas dan Keliling poster tersebut?");
   gotoxy(46,17);textcolor(30);cprintf("a. 400 m2 dan 80 m");
   gotoxy(46,18);textcolor(30);cprintf("b. 450 m2 dan 87 m");
   gotoxy(46,19);textcolor(30);cprintf("c. 500 m2 dan 45 m");
   gotoxy(46,20);textcolor(30);cprintf("d. 300 m2 dan 78 m");
   gotoxy(46,21);textcolor(30);cprintf("Pembahasan");
   gotoxy(46,22);textcolor(30);cprintf("Diketahui");
   gotoxy(46,23);textcolor(30);cprintf("P = 20 m");
   gotoxy(46,24);textcolor(30);cprintf("Masukan Panjang : ");gets(sisi);
   if(strlen(sisi)==0)contoh_p();
   for(int a=0;a<strlen(sisi);a++){
   	if((sisi[a]>='0'&& sisi [a]<='9')&&(sisi[0]!='0')){
      	continue;
      }else{
         gotoxy(46,24);textcolor(30);cprintf("inputan harus berupa bilangan bulat");Sleep(1000);
         gotoxy(46,24);printf("                                                                 ");
         hapus_p();
         contoh_p();

      }
   }
	int keliling,luas;
	gotoxy(46,26);textcolor(30);cprintf("Keliling = 4 x S");getch();
   keliling=atoi(sisi)*4;
	gotoxy(46,27);textcolor(30);cprintf("Keliling = %d",keliling);getch();
	gotoxy(46,28);textcolor(30);cprintf("Luas = S x S");getch();
   luas=atoi(sisi)* atoi(sisi);
	gotoxy(46,29);textcolor(30);cprintf("Luas = %d",luas);getch();
	gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
	char pilih;
	pilih=getch();
   while(pilih!='9')pilih=getch();
	if (pilih=='9'){
   		clrscr();
 			persegi();
	}
}


void contoh_s(){
	char alas [10];
	char tinggi [10];
	char miring[10];
	gotoxy(46,12);textcolor(30);cprintf("1.Hitunglah keliling sebuah segitiga apabila panjang sisi ketiga sudah diketahui");
   gotoxy(46,13);textcolor(30);cprintf(" panjang ketiga sisinya lainnya adalah A=14 cm,T=24 cm,M=26");
	gotoxy(46,14);textcolor(30);cprintf("a. 64 cm");
   gotoxy(46,15);textcolor(30);cprintf("b. 54 cm");
   gotoxy(46,16);textcolor(30);cprintf("c. 44 cm");
   gotoxy(46,17);textcolor(30);cprintf("d. 34 cm");
	gotoxy(46,18);textcolor(30);cprintf("Pembahasan");
   gotoxy(46,19);textcolor(30);cprintf("Diketahui :");
   gotoxy(46,20);textcolor(30);cprintf("Sisi A=14 cm Sisi B=24 cm Sisi C=26 cm");
   gotoxy(46,21);textcolor(30);cprintf("Masukan Sisi A(alas) :");gets(alas);
   if(strlen(alas)==0)contoh_s();
	 for(int a=0;a<strlen(alas);a++){
   	if((alas[a]>='0'&& alas [a]<='9')&&(alas[0]!='0')){
      	continue;
      }else{
         gotoxy(46,21);textcolor(30);cprintf("inputan harus bilangan bulat");Sleep(1000);
         clear(alas,68,21);
         gotoxy(46,21);printf("                                                      ");
         contoh_s();
      }
    }
    gotoxy(46,22);textcolor(30);cprintf("Masukkan Sisi T(Tinggi) :");gets(tinggi);
     bool y=true;
     int z=0;
     while(y==true){
      z=0;
      if(strlen(tinggi)==0)z=1;
    	 for(int a=0;a<strlen(tinggi);a++){
   			if((tinggi[a]>='0'&& tinggi [a]<='9')&&(tinggi[0]!='0')){
               z++;
      		}else{
            	gotoxy(46,22);textcolor(30);cprintf("inputan harus bilangan bulat");
               clear(tinggi,71,22);
         		//getch();
            	gotoxy(46,22);printf("                                                     ");
               gotoxy(46,22);textcolor(30);cprintf("Masukkan Sisi T(Tinggi) :");gets(tinggi);
               break;
     		 	}
     		}
         if(z==strlen(tinggi) && z!=0){
         	y=false;
         }
         /*else{
         	gotoxy(46,22);textcolor(30);cprintf("Masukkan Sisi T(Tinggi) :");gets(tinggi);
         }*/
     }
     y=true;
     gotoxy(46,23);textcolor(30);cprintf("Masukkan Sisi M(Miring) :");gets(miring);
     while(y==true){
      z=0;
      if(strlen(miring)==0)z=1;
    	 for(int a=0;a<strlen(miring);a++){
   			if((miring[a]>='0'&& miring [a]<='9')&&(miring[0]!='0')){
               z++;
      		}else{
            	gotoxy(46,23);textcolor(30);cprintf("inputan harus bilangan bulat");
               clear(miring,71,23);
         		//getch();
            	gotoxy(46,23);printf("                                            ");
               gotoxy(46,23);textcolor(30);cprintf("Masukkan Sisi M(Miring) :");gets(miring);
               break;
     		 	}
     		}
         if(z==strlen(miring) && z!=0){
         	y=false;
         }
         else{
               gotoxy(46,23);textcolor(30);cprintf("Masukkan Sisi M(Miring) :");gets(miring);
     		}
     }

  	int keliling;
	float luas;
   gotoxy(46,25);textcolor(30);cprintf("Keliling = A + T + M");getch();
   keliling = (atoi(alas)+atoi(tinggi))+atoi(miring);
	gotoxy(46,26);textcolor(30);cprintf("Keliling = %d\n",keliling);getch();
	gotoxy(46,27);textcolor(30);cprintf("Luas = 1/2 * A * T");getch();
   luas = atof(alas)*atof(tinggi)/2;
	gotoxy(46,28);textcolor(30);cprintf("Luas = %.2f",luas);getch();
   gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
	char pilih;
	pilih=getch();
   while(pilih!='9')pilih=getch();
	if (pilih=='9'){
   		clrscr();
 			segitiga();
	}
}
void contoh_j(){
	char alas[10];
	char tinggi[10];
	gotoxy(46,14);textcolor(30);cprintf("1.hitunglah keliling dan luas suatu jajargenjang yang");
   gotoxy(46,15);textcolor(30);cprintf("  memiliki sisi alas 15 cm dan tinggi 21 cm");
   gotoxy(46,16);textcolor(30);cprintf("a. 60 cm dan 315 ");
	gotoxy(46,17);textcolor(30);cprintf("b. 72 cm dan 315 ");
   gotoxy(46,18);textcolor(30);cprintf("c. 45 cm dan 200 ");
   gotoxy(46,19);textcolor(30);cprintf("d. 55 cm dan 129 ");
	gotoxy(46,20);textcolor(30);cprintf("Pembahasan");
   gotoxy(46,21);textcolor(30);cprintf("Diketahui :");
   gotoxy(46,22);textcolor(30);cprintf("Sisi Alas 15 cm dan Tinggi 21 cm");
   gotoxy(46,23);textcolor(30);cprintf("Masukan Alas :");gets(alas);
   if(strlen(alas)==0)contoh_j();
	 for(int a=0;a<strlen(alas);a++){
   	if((alas[a]>='0'&& alas [a]<='9')&&(alas[0]!='0')){
      	continue;
      }else{
         gotoxy(46,23);textcolor(30);cprintf("inputan harus bilangan bulat");Sleep(1000);
         clear(alas,60,23);
         gotoxy(46,23);printf("                                                      ");
         contoh_j();
      }
    }
    gotoxy(46,24);textcolor(30);cprintf("Masukkan Lebar :");gets(tinggi);
     bool y=true;
     int z=0;
     while(y==true){
      z=0;
      if(strlen(tinggi)==0)z=1;
    	 for(int a=0;a<strlen(tinggi);a++){
   			if((tinggi[a]>='0'&& tinggi [a]<='9')&&(tinggi[0]!='0')){
               z++;
      		}else{
            	gotoxy(46,24);textcolor(30);cprintf("inputan harus bilangan bulat"); getch();
               clear(tinggi,62,24);
            	gotoxy(46,24);printf("                                                     ");
               gotoxy(46,24);textcolor(30);cprintf("Masukkan Lebar :");gets(tinggi);
               break;
     		 	}
     		}
         if(z==strlen(tinggi) && z!=0){
         	y=false;
         }
         else{
         	gotoxy(46,24);textcolor(30);cprintf("Masukkan Lebar :");gets(tinggi);
         }
     }
     /*gotoxy(46,24);textcolor(30);cprintf("Masukan Tinggi : ");gets(tinggi);
   for(int a=0;a<strlen(alas);a++){
   	if((alas[a]>='0'&& alas [a]<='9')&&(alas[0]!='0')){
      	continue;
      }else{
         hapus_j();
      	gotoxy(46,17);textcolor(30);cprintf("inputan harus berupa bilangan bulat");Sleep(1000);
         gotoxy(46,17);printf("                                   ");
        contoh_j();

      }
   }*/
   int keliling;
	int luas;
	gotoxy(46,25);textcolor(30);cprintf("Keliling = 2(A + T)");getch();
   keliling= 2*(atoi(alas) + atoi(tinggi));
	gotoxy(46,26);textcolor(30);cprintf("Keliling =%d",keliling);getch();
	gotoxy(46,27);textcolor(30);cprintf("Luas = A x T");getch();
   luas=atoi(alas)*atoi(tinggi);
	gotoxy(46,28);textcolor(30);cprintf("Luas = %d",luas);getch();
   gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
   char pilih;
	pilih=getch();
   while(pilih!='9')pilih=getch();
	if (pilih=='9'){
   		clrscr();
 			jajargenjang();
	}

}
void contoh_b(){
	char diagonal1[10];
	char diagonal2[10];
	char sisi[10];
	gotoxy(46,14);textcolor(30);cprintf("1.Tentukanlah keliling dan luas belah ketupat yang memiliki");
   gotoxy(46,15);textcolor(30);cprintf("  panjang sisi 5 cm dan panjang diagonal-diagonalnya 6 cm dan 3 cm");
   gotoxy(46,16);textcolor(30);cprintf("a.20 cm dan 9 cm");
   gotoxy(46,17);textcolor(30);cprintf("b.21 cm dan 10 cm");
   gotoxy(46,18);textcolor(30);cprintf("c.16 cm dan 9 cm");
   gotoxy(46,19);textcolor(30);cprintf("d.13 cm dan 10 cm :");
   gotoxy(46,20);textcolor(30);cprintf("Pembahasaan");
   gotoxy(46,21);textcolor(30);cprintf("Diketahui :");
	gotoxy(46,22);textcolor(30);cprintf("Masukkan Diagonal 1 :");gets(diagonal1);
   if(strlen(diagonal1)==0)contoh_b();
	 for(int a=0;a<strlen(diagonal1);a++){
   	if((diagonal1[a]>='0'&& diagonal1 [a]<='9')&&(diagonal1[0]!='0')){
      	continue;
      }else{
         gotoxy(46,22);textcolor(30);cprintf("inputan harus bilangan bulat");Sleep(1000);
         clear(diagonal1,67,22);
         gotoxy(46,22);printf("                                                      ");
         contoh_b();
      }
    }
    gotoxy(46,23);textcolor(30);cprintf("Masukkan Diagonal 2 :");gets(diagonal2);
     bool y=true;
     int z=0;
     while(y==true){
      z=0;
      if(strlen(diagonal2)==0)z=1;
    	 for(int a=0;a<strlen(diagonal2);a++){
   			if((diagonal2[a]>='0'&& diagonal2 [a]<='9')&&(diagonal2[0]!='0')){
               z++;
      		}else{
            	gotoxy(46,23);textcolor(30);cprintf("inputan harus bilangan bulat");
               clear(diagonal2,67,23);
         		//getch();
            	gotoxy(46,23);printf("                                                     ");
               gotoxy(46,23);textcolor(30);cprintf("Masukkan Diagonal 2 :");gets(diagonal2);
               break;
     		 	}
     		}
         if(z==strlen(diagonal2) && z!=0){
         	y=false;
         }
         else{
         	gotoxy(46,23);textcolor(30);cprintf("Masukkan Diagonal 2 :");gets(diagonal2);
         }
     }
     y=true;
     gotoxy(46,24);textcolor(30);cprintf("Masukkan Sisi :");gets(sisi);
     while(y==true){
      z=0;
      if(strlen(sisi)==0)z=0;
    	 for(int a=0;a<strlen(sisi);a++){
   			if((sisi[a]>='0'&& sisi[a]<='9')&&(sisi[0]!='0')){
               z++;
      		}else{
            	gotoxy(46,24);textcolor(30);cprintf("inputan harus bilangan bulat");
               clear(sisi,61,24);
         		//getch();
            	gotoxy(46,24);printf("                                            ");
               gotoxy(46,24);textcolor(30);cprintf("Masukkan Sisi :");gets(sisi);
               break;
     		 	}
     		}
         if(z==strlen(sisi) && z!=0){
         	y=false;
         }
         else{
               gotoxy(46,24);textcolor(30);cprintf("Masukkan Sisi :");gets(sisi);
     		}
     }


	int keliling;
	int luas;
	gotoxy(46,26);textcolor(30);cprintf("Keliling = 4 * S"); getch();
   keliling = (4*atoi(sisi));
	gotoxy(46,27);textcolor(30);cprintf("Keliling = %d\n",keliling);getch();
   luas=(atoi(diagonal1)*atoi(diagonal2))/2;
	gotoxy(46,28);textcolor(30);cprintf("Luas = D1 * D2 /2");getch();
	gotoxy(46,29);textcolor(30);cprintf("Luas = %d\n",luas);getch();
   gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
	char pilih;
	pilih=getch();
   while(pilih!='9')pilih=getch();
	if (pilih=='9'){
   		clrscr();
 			belah_ketupat();
	}
}
void contoh_l(){
	char diagonal1[10];
	char diagonal2[10];
	char sisi1[10];
	char sisi2[10];
   gotoxy(46,14);textcolor(30);cprintf("CONTOH SOAL");
   gotoxy(46,15);textcolor(30);cprintf("1.Sebuah layang-layang memiliki panjang diagonal horizontal 12 cm (d2)");
   gotoxy(46,16);textcolor(30);cprintf("  dan diagonal vertikal 20 cm (d1)dan memiliki sisi AB = 11 cm dan sisi CD = 13");
   gotoxy(46,17);textcolor(30);cprintf("  Berapakah luas dan keliling layang-layang tersebut?");
   gotoxy(46,18);textcolor(30);cprintf("Pembahasaan");
   gotoxy(46,19);textcolor(30);cprintf("Diketahui :");
   gotoxy(46,20);textcolor(30);cprintf("D1 = 20 cm, D2 = 12 cm, Sisi AB = 11 cm, CD = 13 cm");
	gotoxy(46,21);textcolor(30);cprintf("Masukkan Diagonal 1 :");gets(diagonal1);
   if(strlen(diagonal1)==0)contoh_l();
	 for(int a=0;a<strlen(diagonal1);a++){
   	if((diagonal1[a]>='0'&& diagonal1 [a]<='9')&&(diagonal1[0]!='0')){
      	continue;
      }else{
         gotoxy(46,21);textcolor(30);cprintf("inputan harus bilangan bulat");Sleep(1000);
         clear(diagonal1,67,21);
         gotoxy(46,21);printf("                                                      ");
         contoh_l();
      }
    }
     gotoxy(46,22);textcolor(30);cprintf("Masukkan Diagonal 2 :");gets(diagonal2);
     bool y=true;
     int z;
     while(y==true){
      z=0;
      if(strlen(diagonal2)==0)z=1;
    	 for(int a=0;a<strlen(diagonal2);a++){
   			if((diagonal2[a]>='0'&& diagonal2 [a]<='9')&&(diagonal2[0]!='0')){
               z++;
      		}else{
            	gotoxy(46,22);textcolor(30);cprintf("inputan harus bilangan bulat");
               clear(diagonal2,67,22);
         		//getch();
            	gotoxy(46,22);printf("                                                     ");
               gotoxy(46,22);textcolor(30);cprintf("Masukkan Diagonal 2 :");gets(diagonal2);
               break;
     		 	}
     		}
         if(z==strlen(diagonal2) && z!=0){
         	y=false;
         }
         else{
         	gotoxy(46,22);textcolor(30);cprintf("Masukkan Diagonal 2 :");gets(diagonal2);
         }
     }
     gotoxy(46,23);textcolor(30);cprintf("Masukkan Sisi 1 :");gets(sisi1);
      y=true;
      //int z=0;
     while(y==true){
      z=0;
      if(strlen(sisi1)==0)z=1;
    	 for(int a=0;a<strlen(sisi1);a++){
   			if((sisi1[a]>='0'&& sisi1 [a]<='9')&&(sisi1[0]!='0')){
               z++;
      		}else{
            	gotoxy(46,23);textcolor(30);cprintf("inputan harus bilangan bulat");
               clear(sisi1,63,23);
         		//getch();
            	gotoxy(46,23);printf("                                                     ");
               gotoxy(46,23);textcolor(30);cprintf("Masukkan Sisi 1 :");gets(sisi1);
               break;
     		 	}
     		}
         if(z==strlen(sisi1) && z!=0){
         	y=false;
         }
         else{
         	gotoxy(46,23);textcolor(30);cprintf("Masukkan Sisi 1 :");gets(sisi1);
         }
     }
     y=true;
     gotoxy(46,24);textcolor(30);cprintf("Masukkan Sisi 2 :");gets(sisi2);
     while(y==true){
      int z=0;
      if(strlen(sisi2)==0)z=0;
    	 for(int a=0;a<strlen(sisi2);a++){
   			if((sisi2[a]>='0'&& sisi2[a]<='9')&&(sisi2[0]!='0')){
               z++;
      		}else{
            	gotoxy(46,24);textcolor(30);cprintf("inputan harus bilangan bulat");
               clear(sisi2,63,24);
         		//getch();
            	gotoxy(46,24);printf("                                            ");
               gotoxy(46,24);textcolor(30);cprintf("Masukkan Sisi 2 :");gets(sisi2);
               break;
     		 	}
     		}
         if(z==strlen(sisi2) && z!=0){
         	y=false;
         }
         else{
               gotoxy(46,24);textcolor(30);cprintf("Masukkan Sisi 2 :");gets(sisi2);
     		}
     }

////////////////////////////


	/*gotoxy(46,24);textcolor(30);cprintf("Masukkan Sisi 2     :");gets(sisi2);
   for(int a=0;a<strlen(diagonal1);a++){
   	if((diagonal1[a]>='0'&& diagonal1[a]<='9')&&(diagonal1[0]!='0')){
      	continue;
      }else{
         hapus_l();
         gotoxy(46,21);textcolor(30);cprintf("inputan harus berupa bilangan bulat");Sleep(1000);
         gotoxy(46,21);printf("                                   ");
         contoh_l();
      }
   }
   gotoxy(46,22);textcolor(30);cprintf("Masukkan Diagonal 2 :");gets(diagonal2);
   	int z;
   	y=true;
    	while(y==true){
      z=0;
      if(strlen(diagonal2)==0)z=1;
    	 for(int a=0;a<strlen(diagonal2);a++){
   			if((diagonal2[a]>='0'&& diagonal2 [a]<='9')&&(diagonal2[0]!='0')){
               z++;
      		}else{
            	gotoxy(46,24);textcolor(30);cprintf("inputan harus bilangan bulat");
         		getch();
            	gotoxy(46,24);printf("                                          ");
         		clear(diagonal2,68,22);
               gotoxy(68,22);textcolor(30);gets(diagonal2);
               break;
     		 	}
     		}
         if(z==strlen(diagonal2) && z!=0){
         	y=false;
         }
         else  {
         	gotoxy(68,22);textcolor(30);gets(diagonal2);
     		}
     }
     gotoxy(46,23);textcolor(30);cprintf("Masukkan Sisi 1     :");gets(sisi1);
      y=true;
    	while(y==true){
      z=0;
      if(strlen(sisi1)==0)z=1;
    	 for(int a=0;a<strlen(sisi1);a++){
   			if((diagonal2[a]>='0'&& diagonal2 [a]<='9')&&(diagonal2[0]!='0')){
               z++;
      		}else{
            	gotoxy(46,25);textcolor(30);cprintf("inputan harus bilangan bulat");
         		getch();
            	gotoxy(46,25);printf("                                          ");
         		clear(diagonal2,68,23);
               gotoxy(68,23);textcolor(30);gets(diagonal2);
               break;
     		 	}
     		}
         if(z==strlen(diagonal2) && z!=0){
         	y=false;
         }
         else  {
         	gotoxy(68,23);textcolor(30);gets(diagonal2);
     		}
     } */
   int keliling;
	int luas;
	gotoxy(46,26);textcolor(30);cprintf("Keliling = 2(S + S)");getch();
   keliling = 2* atoi(sisi1)+ 2* atoi(sisi2);
	gotoxy(46,27);textcolor(30);cprintf("Keliling = %d",keliling);getch();
	gotoxy(46,28);textcolor(30);cprintf("Luas =D1 * D2/2");getch();
   luas=atoi(diagonal1)*atoi (diagonal2)/2;
	gotoxy(46,29);textcolor(30);cprintf("Luas = %d",luas); getch();
   gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
	char pilih;
	pilih=getch();
   while(pilih!='9')pilih=getch();
	if (pilih=='9'){
   		clrscr();
 			layang_layang();
	}
}
void contoh_t(){
	char tinggi[10];
	char sisej1[10];
	char sisej2[10];
   char miring[10];
   gotoxy(46,14);textcolor(30);cprintf("CONTOH SOAL");
   gotoxy(46,15);textcolor(30);cprintf("1.Sebuah trapesium memiliki sisi sejajar masing-masing 10 cm");
   gotoxy(46,16);textcolor(30);cprintf("  dan 12 cm  serta memiliki tinggi 8 cm, sisi miring 5 cm");
   gotoxy(46,17);textcolor(30);cprintf("  Berapa keliling dan luas trapesium tersebut?");
   gotoxy(46,18);textcolor(30);cprintf("a.22 cm dan 88 cm");
   gotoxy(46,19);textcolor(30);cprintf("b.22 cm dan 89 cm");
   gotoxy(46,20);textcolor(30);cprintf("c.23 cm dan 67 cm");
   gotoxy(46,21);textcolor(30);cprintf("d.25 cm dan 56 cm");
	gotoxy(46,22);textcolor(30);cprintf("Masukkan Tinggi :");gets(tinggi);
   gotoxy(46,23);textcolor(30);cprintf("Masukkan Sisi Miring :");gets(miring);
	gotoxy(46,24);textcolor(30);cprintf("Masukkan Sisi Sejajar(ss) 1 :");gets(sisej1);
	gotoxy(46,25);textcolor(30);cprintf("Masukkan Sisi Sejajar(ss) 2 :");gets(sisej2);
   for(int a=0;a<strlen(tinggi);a++){
   	if((tinggi[a]>='0'&& tinggi [a]<='9')&&(tinggi[0]!='0')){
      	continue;
      }else{
         hapus_t();
         gotoxy(46,17);textcolor(30);cprintf("inputan harus berupa bilangan bulat");Sleep(1000);
         gotoxy(46,17);printf("                                   ");
         contoh_t();

      }
    }
   int keliling;
	int luas;
   int jml=atoi(sisej1)+atoi(sisej2);
	gotoxy(46,26);textcolor(30);cprintf("Keliling = Sisi sejajar1 + Sisi sejajar*2(sisi miring)");getch();
   keliling=atoi(sisej1)+atoi(sisej2)+2*atoi(miring);
	gotoxy(46,27);textcolor(30);cprintf("Keliling = %d",keliling); getch();
	gotoxy(46,28);textcolor(30);cprintf("Luas=1/2 *jumlah rusuk sejajar*t");getch();
   luas=jml*atoi(tinggi)/2;
	gotoxy(46,29);textcolor(30);cprintf("Luas = %d\n",luas);getch();
   gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");getch();
	char pilih;
	pilih=getch();
   while(pilih!='9')pilih=getch();
	if (pilih=='9'){
   		clrscr();
 			trapesium();
	}
}

void contoh_li(){
		char jari[100];
      gotoxy(46,14);textcolor(30);cprintf("CONTOH SOAL");
      gotoxy(46,15);textcolor(30);cprintf("Sebuah lingkaran memiliki panjang diameter 34 cm");
      gotoxy(46,17);textcolor(30);cprintf("Tentukanlah keliling lingkaran dan luas lingkaran?");
      gotoxy(46,18);textcolor(30);cprintf("Pembahasan");
      gotoxy(46,19);textcolor(30);cprintf("Diketahui :");
      gotoxy(46,20);textcolor(30);cprintf("Diameter 34 cm dan jari-jari 17 cm");
		gotoxy(46,21);textcolor(30);cprintf("Masukkan Jari-Jari :");gets(jari);
       if(strlen(jari)==0)contoh_li();
   for(int a=0;a<strlen(jari);a++){
   	if((jari[a]>='0'&& jari [a]<='9')&&(jari[0]!='0')){
      	continue;
      }else{
         gotoxy(46,21);textcolor(30);cprintf("inputan harus berupa bilangan bulat");Sleep(1000);
         gotoxy(46,21);printf("                                                                 ");
         hapus_p();
         contoh_li();

      }
   }
   	float jar=atof(jari);
   	float diameter=atof(jari)*2;
		float keliling;
		float luas;
		gotoxy(46,23);textcolor(30);cprintf("Keliling =Phi x D");getch();
      keliling= 3.14 * diameter;
		gotoxy(46,24);textcolor(30);cprintf("Keliling = %.2f",keliling); getch();
		gotoxy(46,25);textcolor(30);cprintf("Luas = Phi * R * R"); getch();
      luas= 3.14 * jar *jar;
		gotoxy(46,26);textcolor(30);cprintf("Luas = %.2f",luas); getch();
   	gotoxy(60,33);textcolor(30);cprintf("tekan 9 untuk kembali");
      char pilih;
		pilih=getch();
   	while(pilih!='9')pilih=getch();
			if (pilih=='9'){
   			clrscr();
 				lingkaran();
	     }
}
void latihan_pp(){
	int nilai;
	bingkai();
  	char pilih[2];
	gotoxy(12,5);textcolor(30);cprintf("1.Diketahui sebuah persegi panjang dengan panjang 26 cm dan lebar 18 cm");
  	gotoxy(12,6);textcolor(30);cprintf("  hitunglah luas dari persegi panjang tersebut ?");
	gotoxy(12,7);textcolor(30);cprintf(" A.468                      C.496         ");
	gotoxy(12,8);textcolor(30);cprintf(" B.486                      D.276         ");
	do{
   	gotoxy(12,9);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,10);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         clear(pilih,36,9);
         gotoxy(12,10);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"a")==0||(pilih=="A"))
   		tamp+=1;
	gotoxy(12,11);textcolor(30);cprintf("2.Diketahui sebuah persegi panjang dengan panjang 32 cm dan lebar 22 cm,");
  	gotoxy(12,12);textcolor(30);cprintf("  hitunglah keliling dari persegi panjang tersebut ?");
	gotoxy(12,13);textcolor(30);cprintf(" A.608                     C.704         ");
	gotoxy(12,14);textcolor(30);cprintf(" B.702                     D.614         ");
 	do{
   	gotoxy(12,15);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,16);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         clear(pilih,36,15);
         gotoxy(12,16);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"c")==0||(pilih=="C"))
   		tamp+=1;
  	gotoxy(12,17);textcolor(30);cprintf("3.Diketahui sebuah persegi panjang  dengan luas 96 cm2 dengan panjang 12 cm,");
  	gotoxy(12,18);textcolor(30);cprintf("  carilah lebar dari persegi panjang tersebut ?");
	gotoxy(12,19);textcolor(30);cprintf(" A.5                      C.7         ");
	gotoxy(12,20);textcolor(30);cprintf(" B.6                      D.8         ");
	do{
   	gotoxy(12,21);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,22);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         clear(pilih,36,21);
         gotoxy(12,22);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"d")==0||(pilih=="D"))
   		tamp+=1;
	gotoxy(12,23);textcolor(30);cprintf("4.Diketahui sebuah persegi panjang dengan luas 288 cm2 dengan lebar 12 cm,");
  	gotoxy(12,24);textcolor(30);cprintf("  carilah panjang dari persegi panjang tersebut ?");
	gotoxy(12,25);textcolor(30);cprintf(" A.22                      C.24       ");
	gotoxy(12,26);textcolor(30);cprintf(" B.23                      D.25       ");
	do{
   	gotoxy(12,27);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,28);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         clear(pilih,36,27);
         gotoxy(12,28);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"c")==0||(pilih=="C"))
   		tamp+=1;
	gotoxy(12,29);textcolor(30);cprintf("5.Diketahui sebuah persegi panjang dengan luas 220 cm2 dengan panjang 22 cm,");
  	gotoxy(12,30);textcolor(30);cprintf("  carilah lebar dari persegi panjang tersebut ?");
	gotoxy(12,31);textcolor(30);cprintf(" A.10                      C.30       ");
	gotoxy(12,32);textcolor(30);cprintf(" B.20                      D.40       ");
	do{
   	gotoxy(12,33);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,34);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         clear(pilih,36,33);
         gotoxy(12,34);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"a")==0||(pilih=="A"))
   		tamp+=1;

  	clrscr();
  	kotak_lat();
  	int poin=tamp;
	if (poin>=4){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA SEMPURNA ");
	}else if(poin<3&&poin>=0){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA JELEK ");
	}
   getch();
   clrscr();
   lagi();
}


void latihan_p(){
	char pilih[3];
   int nilai;
   bingkai();
	gotoxy(12,5);textcolor(30);cprintf("1.Diketahui sebuah persegi dengan sisi 26 cm ,hitunglah luas dari persegi tersebut ?");
	gotoxy(12,6);textcolor(30);cprintf(" A.576                      C.676         ");
	gotoxy(12,7);textcolor(30);cprintf(" B.476                      D.876         ");
	do{
   	gotoxy(12,8);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
      	clear(pilih,36,8);
   		gotoxy(12,9);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,8);printf(" ");
         }
         gotoxy(12,9);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"c")==0||(pilih=="C"))
   		tamp+=1;
		gotoxy(12,10);textcolor(30);cprintf("2.Diketahui sebuah persegi dengan sisi 32 cm ,hitunglah keliling dari persegi tersebut ?\n");
		gotoxy(12,11);textcolor(30);cprintf(" A.128                     C.102         \n");
		gotoxy(12,12);textcolor(30);cprintf(" B.129                     D.124         \n");
			do{
   	gotoxy(12,13);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
         clear(pilih,36,13);
   		gotoxy(12,14);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,13);printf(" ");
         }
         gotoxy(12,14);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"a")==0||(pilih=="A"))
   		tamp+=1;
   	gotoxy(12,15);textcolor(30);cprintf("3.Diketahui sebuah persegi dengan luas 2025 cm ,carilah sisi dari persegi tersebut ?\n");
		gotoxy(12,16);textcolor(30);cprintf(" A.42                      C.44       \n");
		gotoxy(12,17);textcolor(30);cprintf(" B.43                      D.45       \n");
			do{
   	gotoxy(12,18);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
      	clear(pilih,36,18);
   		gotoxy(12,19);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         int l=strlen(pilih);
         for(int xy=1;xy<=l;xy++){
         	gotoxy(35+xy,18);printf(" ");
         }
         gotoxy(12,19);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"d")==0||(pilih=="D"))
   		tamp+=1;
		gotoxy(12,20);textcolor(30);cprintf("4.Diketahui sebuah persegi dengan luas 1296 cm ,carilah sisi dari persegi tersebut ?\n");
		gotoxy(12,21);textcolor(30);cprintf(" A.35                      C.37       \n");
		gotoxy(12,22);textcolor(30);cprintf(" B.36                      D.38       \n");
      do{
   	gotoxy(12,23);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
      	clear(pilih,36,23);
   		gotoxy(12,24);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,23);printf(" ");
         }
         gotoxy(12,24);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"b")==0||(pilih=="B"))
   		tamp+=1;
		gotoxy(12,25);textcolor(30);cprintf("5.Diketahui sebuah persegi dengan luas 2025 cm ,carilah sisi dari persegi tersebut ?\n");
		gotoxy(12,26);textcolor(30);cprintf(" A.42                      C.44       \n");
		gotoxy(12,27);textcolor(30);cprintf(" B.43                      D.45       \n");
 	do{
   	gotoxy(12,28);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
      	clear(pilih,36,28);
   		gotoxy(12,29);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,28);printf(" ");
         }
         gotoxy(12,29);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"d")==0||(pilih=="D"))
   		tamp+=1;
		clrscr();
   	kotak_lat();
   	int poin=tamp;
   if (poin>=4){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA SEMPURNA ");
	}else if(poin<3&&poin>=0){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA JELEK ");
	}
   getch();
   clrscr();
   lagi_p();
}



void latihan_s(){
	int nilai;
	bingkai();
  	char pilih[2];
	gotoxy(12,5);textcolor(30);cprintf("1.Diketahui sebuah segitiga dengan luas 90 cm2 dengan alas 20 cm,");
  	gotoxy(12,6);textcolor(30);cprintf("  carilah tinggi dari segitiga tersebut");
	gotoxy(12,7);textcolor(30);cprintf(" A.8                       C.10     ");
	gotoxy(12,8);textcolor(30);cprintf(" B.9                       D.11     ");
		do{
   	gotoxy(12,9);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
      	clear(pilih,36,9);
         gotoxy(12,9);textcolor(30);cprintf(" ");
   		gotoxy(12,10);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,9);printf(" ");
         }
         gotoxy(12,10);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"b")==0||(pilih=="B"))
   		tamp+=1;
	gotoxy(12,11);textcolor(30);cprintf("2.Diketahui sebuah segitiga dengan tinggi 15 cm dan dengan alas 20 cm  ,");
  	gotoxy(12,12);cprintf("hitunglah luas dari segitiga tersebut ?");
	gotoxy(12,13);cprintf(" A.150                     C.100      ");
	gotoxy(12,14);cprintf(" B.160                     D.110      ");
  	do{
   	gotoxy(12,15);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
      	clear(pilih,36,15);
   		gotoxy(12,16);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,15);printf(" ");
         }
         gotoxy(12,16);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"a")==0||(pilih=="A"))
		tamp+=1;
	gotoxy(12,17);textcolor(30);cprintf("3.Diketahui sebuah segitiga dengan tinggi 10 cm dan dengan alas 24 cm  ,");
  	gotoxy(12,18);textcolor(30);cprintf("hitunglah keliling dari segitiga tersebut ?");
	gotoxy(12,19);textcolor(30);cprintf(" A.150                     C.100      ");
	gotoxy(12,20);textcolor(30);cprintf(" B.160                     D.110      ");
   do{
   	gotoxy(12,21);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
      	clear(pilih,36,21);
   		gotoxy(12,22);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,21);printf(" ");
         }
         gotoxy(12,22);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"c")==0||(pilih=="C"))
   		tamp+=1;
  	gotoxy(12,23);textcolor(30);cprintf("4.Diketahui sebuah segitiga dengan tinggi 10 cm dengan alas 36 cm  ,");
  	gotoxy(12,24);textcolor(30);cprintf("hitunglah luas dari segitiga tersebut ?");
	gotoxy(12,25);textcolor(30);cprintf(" A.150                     C.170       ");
	gotoxy(12,26);textcolor(30);cprintf(" B.160                     D.180       ");
	do{
   	gotoxy(12,27);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
      	clear(pilih,36,27);
   		gotoxy(12,28);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,27);printf(" ");
         }
         gotoxy(12,28);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"d")==0||(pilih=="D"))
   		tamp+=1;
  	gotoxy(12,29);textcolor(30);cprintf("5.Diketahui sebuah segitiga dengan tinggi 9 cm dengan sisi miring 15 cm  ,");
  	gotoxy(12,30);textcolor(30);cprintf("hitunglah luas dari segitiga tersebut ?");
	gotoxy(12,31);textcolor(30);cprintf(" A.55                      C.53     ");
	gotoxy(12,32);textcolor(30);cprintf(" B.54                      D.52     ");
	do{
   	gotoxy(12,33);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
      	clear(pilih,36,33);
   		gotoxy(12,34);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,33);printf(" ");
         }
         gotoxy(12,34);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"b")==0||(pilih=="B"))
   		tamp+=1;
  	clrscr();
  	kotak_lat();
   int poin=tamp;
		if (poin>=4){
   		textcolor(3);
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA SEMPURNA ");
	}else if(poin<3&&poin>=0){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA JELEK ");
	}
   getch();
   clrscr();
   lagi_s();
}

void latihan_j(){     //////////////////////////yg baru dikasih validasi untuk soal ////////////////////////////////////////////
   bingkai();
   int nilai;
  	char pilih[2];
	gotoxy(12,4);textcolor(30);cprintf("1.Diketahui sebuah jajargenjang dengan tinggi 8 cm dengan alas 16 cm  ,");
  	gotoxy(12,5);textcolor(30);cprintf(" hitunglah luas dari jajargenjang tersebut ?");
	gotoxy(12,6);textcolor(30);cprintf(" A.32                    C.64     ");
	gotoxy(12,7);textcolor(30);cprintf(" B.16                    D.128    ");
   do{
   	gotoxy(12,8);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,9);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,8);printf(" ");
         }
         gotoxy(12,9);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"d")==0||(pilih=="D"))
   		tamp+=1;
  	gotoxy(12,11);textcolor(30);cprintf("2.Diketahui sebuah jajargenjang dengan luas 504 cm2 dengan alas 14 cm  ,");
  	gotoxy(12,12);textcolor(30);cprintf(" hitunglah tinggi dari jajargenjang tersebut ?");
	gotoxy(12,13);textcolor(30);cprintf(" A.33                      C.36     ");
	gotoxy(12,14);textcolor(30);cprintf(" B.46                      D.24     ");
  	do{
   	gotoxy(12,15);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,16);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,15);printf(" ");
         }
         gotoxy(12,16);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"c")==0||(pilih=="C"))
   		tamp+=1;
  	gotoxy(12,18);textcolor(30);cprintf("3.Diketahui sebuah jajargenjang dengan tinggi 16 cm dengan alas 24 cm  ,");
  	gotoxy(12,19);textcolor(30);cprintf(" hitunglah keliling dari jajargenjang tersebut ?");
	gotoxy(12,20);textcolor(30);cprintf(" A.40                      C.12      ");
	gotoxy(12,21);textcolor(30);cprintf(" B.80                      D.76      ");
  	do{
   	gotoxy(12,22);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,23);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,22);printf(" ");
         }
         gotoxy(12,23);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"b")==0||(pilih=="B"))
   		tamp+=1;
  	gotoxy(12,24);textcolor(30);cprintf("4.Diketahui sebuah jajargenjang dengan tinggi 18 cm dengan alas 34 cm  ,");
  	gotoxy(12,25);textcolor(30);cprintf(" hitunglah luas dari jajargenjang tersebut ?");
	gotoxy(12,26);textcolor(30);cprintf(" A.104                     C.306        ");
	gotoxy(12,27);textcolor(30);cprintf(" B.520                     D.612        ");
  	do{
   	gotoxy(12,28);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,29);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,28);printf(" ");
         }
         gotoxy(12,29);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"d")==0||(pilih=="D"))
   		tamp+=1;
  	gotoxy(12,31);textcolor(30);cprintf("5.Diketahui sebuah jajargenjang dengan tinggi 28 cm dengan alas 32 cm  ,");
  	gotoxy(12,32);textcolor(30);cprintf(" hitunglah keliling dari jajargenjang tersebut ?");
	gotoxy(12,33);textcolor(30);cprintf(" A.320                     C.120        ");
	gotoxy(12,34);textcolor(30);cprintf(" B.160                     D.124        ");
  	do{
   	gotoxy(12,35);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,36);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,35);printf(" ");
         }
         gotoxy(12,36);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"c")==0||(pilih=="C"))
   		tamp+=1;
  	clrscr();
  	kotak_lat();
  	int poin=tamp;
		if (poin>=4){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA SEMPURNA ");
	}else if(poin<3&&poin>=0){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA JELEK ");
	}
   getch();
   clrscr();
   lagi_j();
}
void latihan_b(){     /////////////////////////ini juga
  	bingkai();
   int nilai;
  	char pilih[2];
 	gotoxy(12,2);textcolor(30);cprintf("1.Diketahui sebuah belah ketupat dengan panjang diagonalnya 12 cm,");
  	gotoxy(12,3);textcolor(30);cprintf("  dan 8 cm,hitunglah luas dari belah ketupat tersebut ?");
	gotoxy(12,4);textcolor(30);cprintf(" A.48                      C.28     ");
	gotoxy(12,5);textcolor(30);cprintf(" A.39                      D.40      ");
  	do{
   	gotoxy(12,6);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,7);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,6);printf(" ");
         }
         gotoxy(12,7);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"a")==0||(pilih=="A"))
   		tamp+=1;
  	gotoxy(12,9);textcolor(30);cprintf("2.Diketahui sebuah belah ketupat dengan luas 128 cm2,");
  	gotoxy(12,10);textcolor(30);cprintf(" carilah panjang diagonal dari belah ketupat tersebut ?");
	gotoxy(12,11);textcolor(30);cprintf(" A.12                      C.16        ");
	gotoxy(12,12);textcolor(30);cprintf(" B.14                      D.18        ");
  	do{
   	gotoxy(12,13);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,14);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,13);printf(" ");
         }
         gotoxy(12,14);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"c")==0||(pilih=="C"))
   		tamp+=1;
  	gotoxy(12,16);textcolor(30);cprintf("3.Diketahui sebuah belah ketupat dengan panjang sisinya 18 cm,");
  	gotoxy(12,17);textcolor(30);cprintf("  hitunglah keliling dari belah ketupat tersebut ?");
	gotoxy(12,18);textcolor(30);cprintf(" A.52                      C.82        ");
	gotoxy(12,19);textcolor(30);cprintf(" B.62                      D.72        ");
  	do{
   	gotoxy(12,20);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,21);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,20);printf(" ");
         }
         gotoxy(12,21);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"d")==0||(pilih=="D"))
   		tamp+=1;
  	gotoxy(12,23);textcolor(30);cprintf("4.Diketahui sebuah belah ketupat dengan panjang diagonal 26,");
  	gotoxy(12,24);textcolor(30);cprintf("  hitunglah luas dari belah ketupat tersebut ?");
	gotoxy(12,25);textcolor(30);cprintf(" A.288                     C.676       ");
	gotoxy(12,26);textcolor(30);cprintf(" B.338                     D.576       ");
   do{
   	gotoxy(12,27);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,28);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,27);printf(" ");
         }
         gotoxy(12,28);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"b")==0||(pilih=="B"))
   		tamp+=1;
   gotoxy(12,30);textcolor(30);cprintf("5.Diketahui sebuah belah ketupat dengan panjang sisinya 25,");
   gotoxy(12,31);textcolor(30);cprintf("  hitunglah keliling dari belah ketupat tersebut ?");
	gotoxy(12,32);textcolor(30);cprintf(" A.100                     C.200       ");
	gotoxy(12,33);textcolor(30);cprintf(" B.501                     D.208       ");
   do{
   	gotoxy(12,34);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,35);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,34);printf(" ");
         }
         gotoxy(12,35);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"a")==0||(pilih=="A"))
   		tamp+=1;
   clrscr();
   kotak_lat();
   int poin=tamp;
		if (poin>=4){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA SEMPURNA ");
	}else if(poin<3&&poin>=0){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA JELEK ");
	}
   getch();
   clrscr();
   lagi_b();
}
void latihan_l(){
	bingkai();
   int nilai;
	char pilih[2];
	gotoxy(12,3);textcolor(30);cprintf("1.Diketahui sebuah layang-layang dengan panjang diagonalnya 14 cm");
	gotoxy(12,4);textcolor(30);cprintf("  dan diagonal nya 18 cm,hitunglah luas layang-layang tersebut?");
	gotoxy(12,5);textcolor(30);cprintf(" A.122                      C.126       ");
	gotoxy(12,6);textcolor(30);cprintf(" B.112                      D.116       ");
	do{
   	gotoxy(12,7);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,8);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,7);printf(" ");
         }
         gotoxy(12,8);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"c")==0||(pilih=="C"))
   		tamp+=1;
   gotoxy(12,10);textcolor(30);cprintf("2.Diketahui sebuah layang-layang dengan panjang diagonal nya 23 cm dan");
   gotoxy(12,11);textcolor(30);cprintf("  luasnya 299 cm2,carilah diagonal dari layang-layang tersebut ?");
	gotoxy(12,12);textcolor(30);cprintf(" A.28                      C.27        ");
	gotoxy(12,13);textcolor(30);cprintf(" B.29                      D.26        ");
	do{
   	gotoxy(12,14);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,15);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,14);printf(" ");
         }
         gotoxy(12,15);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"d")==0||(pilih=="D"))
   		tamp+=1;
   gotoxy(12,17);textcolor(30);cprintf("3.Diketahui sebuah layang-layang dengan panjang diagonalnya 18 cm dan,");
   gotoxy(12,18);textcolor(30);cprintf("  panjang diagonal nya 24 cm,hitunglah luas dari layang-layang tersebut ?");
	gotoxy(12,19);textcolor(30);cprintf(" A.216                     C.226      ");
	gotoxy(12,20);textcolor(30);cprintf(" B.296                     D.432      ");
	do{
   	gotoxy(12,21);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,22);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,21);printf(" ");
         }
         gotoxy(12,22);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"a")==0||(pilih=="A"))
   		tamp+=1;
   gotoxy(12,24);textcolor(30);cprintf("4.Diketahui sebuah layang-layang dengan panjang sisinya 23 cm dan panjang");
   gotoxy(12,25);textcolor(30);cprintf("  sisi nya 26 cm,hitunglah keliling dari layang-layang tersebut ?");
	gotoxy(12,26);textcolor(30);cprintf(" A.98                      C.76        ");
	gotoxy(12,27);textcolor(30);cprintf(" B.89                      D.67        ");
	do{
   	gotoxy(12,28);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,29);textcolor(30);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,28);printf(" ");
         }
         gotoxy(12,29);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"a")==0||(pilih=="A"))
   		tamp+=1;
   gotoxy(12,31);textcolor(30);cprintf("5.Diketahui sebuah layang-layang dengan panjang sisinya 12 cm dan panjang ");
   gotoxy(12,32);textcolor(30);cprintf("  sisi nya 34 cm,hitunglah keliling dari layang-layang tersebut ?");
	gotoxy(12,33);textcolor(30);cprintf(" A.408                     C.92        ");
	gotoxy(12,34);textcolor(30);cprintf(" B.204                     D.82        ");
	do{
   	gotoxy(12,35);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,36);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,35);printf(" ");
         }
         gotoxy(12,36);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"c")==0||(pilih=="C"))
   		tamp+=1;
   clrscr();
   kotak_lat();
   int poin=tamp;
		if (poin>=4){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA SEMPURNA ");
	}else if(poin<3&&poin>=0){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA JELEK ");
	}
   getch();
   clrscr();
   lagi_l();
}
void latihan_t(){
	bingkai();
   int nilai;
	char pilih[2];
 	gotoxy(12,3);textcolor(30);cprintf("1.Diketahui sebuah trapesium dengan sisi sejajar 12 cm dan 16 cm,");
   gotoxy(12,4);textcolor(30);cprintf("  sisi samping 6 cm,hitunglah keliling dari trapesium tersebut ?");
	gotoxy(12,5);textcolor(30);cprintf(" A.34                    C.40           ");
	gotoxy(12,6);textcolor(30);cprintf(" B.44                    D.50           ");
   do{
   	gotoxy(12,7);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,8);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,7);printf(" ");
         }
         gotoxy(12,8);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"a")==0||(pilih=="A"))
   		tamp+=1;
   gotoxy(12,10);textcolor(30);cprintf("1.Diketahui sebuah trapesium dengan sisi sejajar 12 cm dan 16 cm,");
   gotoxy(12,11);textcolor(30);cprintf("  tinggi 5 cm,hitunglah luas dari trapesium tersebut ?");
	gotoxy(12,12);textcolor(30);cprintf(" A.60                      C.60        ");
	gotoxy(12,13);textcolor(30);cprintf(" B.70                      D.50        ");
   do{
   	gotoxy(12,14);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,15);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,14);printf(" ");
         }
         gotoxy(12,15);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"b")==0||(pilih=="B"))
   		tamp+=1;
   gotoxy(12,17);textcolor(30);cprintf("3.Diketahui sebuah trapesium dengan sisi sejajar 16 cm dan 20 cm,");
   gotoxy(12,18);textcolor(30);cprintf("  sisi samping 7 cm,hitunglah keliling dari trapesium tersebut?");
	gotoxy(12,19);textcolor(30);cprintf(" A.70                      C.43        ");
	gotoxy(12,20);textcolor(30);cprintf(" B.30                      D.50        ");
   do{
   	gotoxy(12,21);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,22);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,21);printf(" ");
         }
         gotoxy(12,22);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"c")==0||(pilih=="C"))
   		tamp+=1;
   gotoxy(12,24);textcolor(30);cprintf("4.Diketahui sebuah trapesium dengan sisi sejajar 20 cm dan 24 cm,");
   gotoxy(12,25);textcolor(30);cprintf("  tinggi 4 cm,hitunglah luas dari trapesium tersebut ?");
   gotoxy(12,26);textcolor(30);cprintf(" A.87                      C.89        ");
   gotoxy(12,27);textcolor(30);cprintf(" B.88                      D.98        ");
   do{
   	gotoxy(12,28);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,29);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,28);printf(" ");
         }
         gotoxy(12,29);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"b")==0||(pilih=="B"))
   		tamp+=1;
   gotoxy(12,31);textcolor(30);cprintf("5.Diketahui sebuah trapesium dengan sisi sejajar 32 cm dan 36 cm,");
   gotoxy(12,32);textcolor(30);cprintf("  sisi samping 16 cm,hitunglah keliling dari trapesium tersebut ?");
	gotoxy(12,33);textcolor(30);cprintf(" A.70                      C.90        ");
	gotoxy(12,34);textcolor(30);cprintf(" B.80                      D.84        ");
   do{
   	gotoxy(12,35);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,36);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,35);printf(" ");
         }
         gotoxy(12,36);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"d")==0||(pilih=="D"))
   		tamp+=1;
  	clrscr();
   kotak_lat();
   int poin=tamp;
		if (poin>=4){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA SEMPURNA ");
	}else if(poin<3&&poin>=0){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA JELEK ");
	}
   getch();
   clrscr();
   lagi_t();
}
void latihan_li(){
   	bingkai();
      int nilai;
	char pilih[2];
	gotoxy(12,5);textcolor(30);cprintf("1.Diketahui sebuah lingkaran yang memiliki jari-jari 29 cm,");
   gotoxy(12,6);textcolor(30);cprintf("  hitunglah keliling dari lingkaran tersebut?");
	gotoxy(12,7);textcolor(30);cprintf("A.182.12                   C.172.12    ");
	gotoxy(12,8);textcolor(30);cprintf("B.192.12                   D.162.12    ");
	do{
   	gotoxy(12,9);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,10);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,9);printf(" ");
         }
         gotoxy(12,10);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"a")==0||(pilih=="A"))
   		tamp+=1;
	gotoxy(12,11);textcolor(30);cprintf("2.Diketahui sebuah lingkaran yang memiliki jari-jari 16 cm,");
   gotoxy(12,12);textcolor(30);cprintf("  hitunglah luas dari lingkaran tersebut?");
	gotoxy(12,13);textcolor(30);cprintf("A.408.24                   C.803.84      ");
	gotoxy(12,14);textcolor(30);cprintf("B.500.78                   D.709.24      ");
	do{
   	gotoxy(12,15);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,16);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,15);printf(" ");
         }
         gotoxy(12,16);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"c")==0||(pilih=="C"))
   		tamp+=1;
	gotoxy(12,16);textcolor(30);cprintf("3.Diketahui sebuah lingkaran yang memiliki luas 200.96 cm2,");
   gotoxy(12,17);textcolor(30);cprintf("  carilah jari-jari dari lingkaran tersebut?");
	gotoxy(12,18);textcolor(30);cprintf("A.6                 C.8    ");
	gotoxy(12,19);textcolor(30);cprintf("B.7                 D.9    ");
	do{
   	gotoxy(12,20);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,21);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,20);printf(" ");
         }
         gotoxy(12,21);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"c")==0||(pilih=="C"))
   		tamp+=1;
	gotoxy(12,23);textcolor(30);cprintf("4.Diketahui sebuah lingkaran yang memiliki keliling 113.04 cm,");
   gotoxy(12,24);textcolor(30);cprintf("   carilah jari-jari dari lingkaran tersebut?");
	gotoxy(12,25);textcolor(30);cprintf("a.18						 c.28");
	gotoxy(12,26);textcolor(30);cprintf("b.26                 d.48");
	do{
   	gotoxy(12,27);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,28);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,27);printf(" ");
         }
         gotoxy(12,28);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"a")==0||(pilih=="A"));
   		tamp+=1;
	gotoxy(12,30);textcolor(30);cprintf("5.Diketahui sebuah lingkaran yang memiliki jari-jari 19 cm,");
   gotoxy(12,31);textcolor(30);cprintf("  hitunglah keliling dari lingkaran tersebut?");
	gotoxy(12,32);textcolor(30);cprintf("A.112.32                  C.119.12     ");
	gotoxy(12,33);textcolor(30);cprintf("B.119.32                  D.111.12     ");
	do{
   	gotoxy(12,34);textcolor(30);cprintf(" Masukkan jawaban anda :");gets(pilih);
      strlwr(pilih);
   	if (strcmp(pilih,"a")==0||strcmp(pilih,"b")==0||strcmp(pilih,"c")==0||strcmp(pilih,"d")==0){
   		nilai=0;
   	}else{
   		gotoxy(12,35);textcolor(30);cprintf("inputan salah!!!!");
         getch();
         nilai=1;
         for(int xy=1;xy<=strlen(pilih);xy++){
         	gotoxy(35+xy,34);printf(" ");
         }
         gotoxy(12,35);printf("                       ");
   	}
   }while(nilai==1);
	if (strcmp(pilih,"b")==0||(pilih=="D"))
   		tamp+=1;
	clrscr();
   kotak_lat();
   int poin=tamp;
		if (poin>=4){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA SEMPURNA ");
	}else if(poin<3&&poin>=0){
   		gotoxy(60,17);textcolor(30);cprintf("SKOR = %d",poin);
   		gotoxy(57,19);textcolor(30);cprintf("NILAI ANDA JELEK ");
	}
   getch();
   clrscr();
   lagi_li();
}
void lagi(){
   char lagii[2];
   kotak_lat();
   gotoxy(55,20);textcolor(30);cprintf("INGIN MENCOBA LAGI(Y/N)? ");
   gotoxy(79,20);gets(lagii);
   if((strcmp(lagii,"y")==0) ||(strcmp(lagii,"Y")==0)){
   	clrscr();
      latihan_pp();
   }else if((strcmp(lagii,"n")==0)||(strcmp(lagii,"N")==0)){
     	clrscr();
  		persegi_panjang();
  	}else{
   	clrscr();
      lagi();
   }
}
void lagi_p(){
   char lagii[2];
   kotak_lat();
   gotoxy(55,20);textcolor(30);cprintf("INGIN MENCOBA LAGI(Y/N)? ");
   gotoxy(79,20);gets(lagii);
   if((strcmp(lagii,"y")==0) ||(strcmp(lagii,"Y")==0)){
   	clrscr();
      latihan_p();
   }else if((strcmp(lagii,"n")==0)||(strcmp(lagii,"N")==0)){
     	clrscr();
  		persegi();
  	}else{
   	clrscr();
      lagi_p();
   }
}
void lagi_s(){
   char lagii[2];
   kotak_lat();
   gotoxy(55,20);textcolor(30);cprintf("INGIN MENCOBA LAGI(Y/N)? ");
   gotoxy(79,20);gets(lagii);
   if((strcmp(lagii,"y")==0) ||(strcmp(lagii,"Y")==0)){
   	clrscr();
      latihan_s();
   }else if((strcmp(lagii,"n")==0)||(strcmp(lagii,"N")==0)){
     	clrscr();
  		segitiga();
  	}else{
   	clrscr();
      lagi_s();
   }
}
void lagi_j(){
   char lagii[2];
   kotak_lat();
   gotoxy(55,20);textcolor(30);cprintf("INGIN MENCOBA LAGI(Y/N)? ");
   gotoxy(79,20);gets(lagii);
   if((strcmp(lagii,"y")==0) ||(strcmp(lagii,"Y")==0)){
   	clrscr();
      latihan_s();
   }else if((strcmp(lagii,"n")==0)||(strcmp(lagii,"N")==0)){
     	clrscr();
  		jajargenjang();
  	}else{
   	clrscr();
      lagi_j();
   }
}
void lagi_b(){
   char lagii[2];
   kotak_lat();
   gotoxy(55,20);textcolor(30);cprintf("INGIN MENCOBA LAGI(Y/N)? ");
   gotoxy(79,20);gets(lagii);
   if((strcmp(lagii,"y")==0) ||(strcmp(lagii,"Y")==0)){
   	clrscr();
      latihan_s();
   }else if((strcmp(lagii,"n")==0)||(strcmp(lagii,"N")==0)){
     	clrscr();
  		belah_ketupat();
  	}else{
   	clrscr();
      lagi_b();
   }
}
void lagi_l(){
   char lagii[2];
   kotak_lat();
   gotoxy(55,20);textcolor(30);cprintf("INGIN MENCOBA LAGI(Y/N)? ");
   gotoxy(79,20);gets(lagii);
   if((strcmp(lagii,"y")==0) ||(strcmp(lagii,"Y")==0)){
   	clrscr();
      latihan_s();
   }else if((strcmp(lagii,"n")==0)||(strcmp(lagii,"N")==0)){
     	clrscr();
  		layang_layang();
  	}else{
   	clrscr();
      lagi_l();
   }
}
void lagi_t(){
   char lagii[2];
   kotak_lat();
   gotoxy(55,20);textcolor(30);cprintf("INGIN MENCOBA LAGI(Y/N)? ");
   gotoxy(79,20);gets(lagii);
   if((strcmp(lagii,"y")==0) ||(strcmp(lagii,"Y")==0)){
   	clrscr();
      latihan_s();
   }else if((strcmp(lagii,"n")==0)||(strcmp(lagii,"N")==0)){
     	clrscr();
  		trapesium();
  	}else{
   	clrscr();
      lagi_t();
   }
}
void lagi_li(){
   char lagii[2];
   kotak_lat();
   gotoxy(55,20);textcolor(30);cprintf("INGIN MENCOBA LAGI(Y/N)? ");
   gotoxy(79,20);gets(lagii);
   if((strcmp(lagii,"y")==0) ||(strcmp(lagii,"Y")==0)){
   	clrscr();
      latihan_s();
   }else if((strcmp(lagii,"n")==0)||(strcmp(lagii,"N")==0)){
     	clrscr();
  		lingkaran();
  	}else{
   	clrscr();
      lagi_li();
   }
}
void clear(char t[],int x,int y){
	for(int a=0;a<strlen(t);a++){
   	gotoxy(x+a,y);printf(" ");
   }
}
int main(){
//contoh_s();
//contoh_pp();
//contoh_b();
	login();
	getch();
}