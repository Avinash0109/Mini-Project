# Mini-Project
import javax.swing.*;
import java.awt.*;
import java.awt.event.*;

class project{
	public static void main(String args[]){
		JFrame frame = new JFrame();
		frame.setVisible(true);
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame.setBounds(100,100,1000,500);
		frame.setTitle("ASY Engineering Guide");
		JTextField t1;
		JPasswordField pass;
		JButton button,button11;
		t1=new JTextField();
		pass=new JPasswordField();
		button =new JButton("Login");
		t1.setBounds(420,250,180,30);
		pass.setBounds(420,290,180,30);
		button.setBounds(460,340,80,20);
		frame.getContentPane().add(t1);
		frame.getContentPane().add(pass);
		frame.getContentPane().add(button);
		Container c = frame.getContentPane();
		c.setLayout(null);
		c.setBackground(Color.WHITE);
		ImageIcon icon = new ImageIcon("logo.png");
		frame.setIconImage(icon.getImage());
		frame.setResizable(false);
		JLabel label = new JLabel("User ID");
		label.setBounds(300,250,100,30);
		JLabel label2 = new JLabel("Password");
		label2.setBounds(300,290,100,30);
		JLabel label3 = new JLabel(icon);
		label3.setBounds(400,50,200,200);
		JLabel label4 = new JLabel("ASY ENGINEERING GUIDE");
		label4.setBounds(425,7,175,100);
		c.add(label);
		c.add(label2);
		c.add(label3);
		c.add(label4);
		JMenuBar menuBar = new JMenuBar();
		frame.setJMenuBar(menuBar);	
		JMenu mnNewMenu = new JMenu("Settings");
		menuBar.add(mnNewMenu);		
		JMenuItem mntmNewMenuItem = new JMenuItem("Please Log In First");
		mnNewMenu.add(mntmNewMenuItem);
		
		JFrame frame2 = new JFrame();
		frame2.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame2.setBounds(100,100,1000,500);
		Container c2 = frame2.getContentPane();
		c2.setLayout(null);
		c2.setBackground(Color.WHITE);
		frame2.setTitle("ASY Engineering Guide");
		JLabel label5 = new JLabel(icon);
		frame2.getContentPane().add(label5);
		label5.setBounds(750,10,200,200);
		JLabel label6 = new JLabel("Departments");
		frame2.getContentPane().add(label6);
		label6.setBounds(435,55,200,200);
		JButton button2,button3,button4,button9;
		button2 = new JButton("Electronics");
		button3 = new JButton("Computer Science");
		button4 = new JButton("Information Technology");
		button2.setBounds(380,200,180,20);
		button3.setBounds(380,240,180,20);
		button4.setBounds(380,280,180,20);
		frame2.getContentPane().add(button2);
		frame2.getContentPane().add(button3);
		frame2.getContentPane().add(button4);
		JMenuBar menuBar2 = new JMenuBar();
		frame2.setJMenuBar(menuBar2);
		JMenu mnNewMenu2 = new JMenu("Settings");
		menuBar2.add(mnNewMenu2);
		JMenuItem mntmNewMenuItem2 = new JMenuItem("Log Out");
		mnNewMenu2.add(mntmNewMenuItem2);
		
		JFrame frame3 = new JFrame();
		frame3.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame3.setBounds(100,100,1000,500);
		Container c3 = frame3.getContentPane();
		c3.setLayout(null);
		c3.setBackground(Color.WHITE);
		frame3.setTitle("ASY Engineering Guide");
		JLabel label12 = new JLabel(icon);
		frame3.getContentPane().add(label12);
		label12.setBounds(770,05,200,200);
		JLabel label9 = new JLabel("Year");
		frame3.getContentPane().add(label9);
		label9.setBounds(425,60,200,200);
		JButton button5,button6,button7,button8,button10;
		button5 = new JButton("First Year");
		button6 = new JButton("Second Year");
		button7 = new JButton("Third Year");
		button8 = new JButton("Fourth Year");
		button10 = new JButton("Back");
		button5.setBounds(280,200,150,20);
		button6.setBounds(450,200,150,20);
		button7.setBounds(280,250,150,20);
		button8.setBounds(450,250,150,20);
		button10.setBounds(375,330,120,20);
		frame3.getContentPane().add(button5);
		frame3.getContentPane().add(button6);
		frame3.getContentPane().add(button7);
		frame3.getContentPane().add(button8);
		frame3.getContentPane().add(button10);	
		JMenuBar menuBar3 = new JMenuBar();
		frame3.setJMenuBar(menuBar3);
		JMenu mnNewMenu3 = new JMenu("Settings");
		menuBar3.add(mnNewMenu3);
		JMenuItem mntmNewMenuItem3 = new JMenuItem("Log Out");
		mnNewMenu3.add(mntmNewMenuItem3);

		JFrame frame4 = new JFrame();
		frame4.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame4.setBounds(100,100,1000,500);
		Container c4 = frame4.getContentPane();
		c4.setLayout(null);
		c4.setBackground(Color.WHITE);
		frame4.setTitle("ASY Engineering Guide");
		JLabel label10 = new JLabel(icon);
		frame4.getContentPane().add(label10);
		label10.setBounds(770,05,200,200);
		JLabel label11 = new JLabel("Year");
		frame4.getContentPane().add(label11);
		label11.setBounds(425,60,200,200);
		JButton button13,button14,button15,button16,button17;
		button13 = new JButton("First Year");
		button14 = new JButton("Second Year");
		button15 = new JButton("Third Year");
		button16 = new JButton("Fourth Year");
		button17 = new JButton("Back");
		button13.setBounds(280,200,150,20);
		button14.setBounds(450,200,150,20);
		button15.setBounds(280,250,150,20);
		button16.setBounds(450,250,150,20);
		button17.setBounds(375,330,120,20);
		frame4.getContentPane().add(button13);
		frame4.getContentPane().add(button14);
		frame4.getContentPane().add(button15);
		frame4.getContentPane().add(button16);
		frame4.getContentPane().add(button17);	
		JMenuBar menuBar4 = new JMenuBar();
		frame4.setJMenuBar(menuBar4);	
		JMenu mnNewMenu4 = new JMenu("Settings");
		menuBar4.add(mnNewMenu4);		
		JMenuItem mntmNewMenuItem4 = new JMenuItem("Log Out");
		mnNewMenu4.add(mntmNewMenuItem4);		
		
		JFrame frame6 = new JFrame();
		frame6.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame6.setBounds(100,100,1000,500);
		Container c6 = frame6.getContentPane();
		c6.setLayout(null);
		c6.setBackground(Color.WHITE);
		frame6.setTitle("ASY Engineering Guide");
		JLabel label7 = new JLabel(icon);
		frame6.getContentPane().add(label7);
		label7.setBounds(770,05,200,200);
		JLabel label8 = new JLabel("Year");
		frame6.getContentPane().add(label8);
		label8.setBounds(425,60,200,200);
		JButton button18,button19,button20,button21,button22;
		button18 = new JButton("First Year");
		button19 = new JButton("Second Year");
		button20 = new JButton("Third Year");
		button21 = new JButton("Fourth Year");
		button22 = new JButton("Back");
		button18.setBounds(280,200,150,20);
		button19.setBounds(450,200,150,20);
		button20.setBounds(280,250,150,20);
		button21.setBounds(450,250,150,20);
		button22.setBounds(375,330,120,20);
		frame6.getContentPane().add(button18);
		frame6.getContentPane().add(button19);
		frame6.getContentPane().add(button20);
		frame6.getContentPane().add(button21);
		frame6.getContentPane().add(button22);
		JMenuBar menuBar6 = new JMenuBar();
		frame6.setJMenuBar(menuBar6);	
		JMenu mnNewMenu6 = new JMenu("Settings");
		menuBar6.add(mnNewMenu6);		
		JMenuItem mntmNewMenuItem6 = new JMenuItem("Log Out");
		mnNewMenu6.add(mntmNewMenuItem6);

		JFrame frame7 = new JFrame();
		frame7.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame7.setBounds(100,100,1000,500);
		Container c7 = frame7.getContentPane();
		c7.setLayout(null);
		c7.setBackground(Color.WHITE);
		frame7.setTitle("ASY Engineering Guide");	
		String data[][]={         {"Applied Mathematics","Engineering Mathematics","Grewal B S "},    
                          		  {"Physics","Engineering Physics","Dattuprasad Joshi"},    
                          		  {"Chemistry ","Chemistry for Engineers","B K Ambasta"},
			  		  {"BEE","Basic Electrical Engineering","P S Dogal"},
			  		  {"Applied mathematics - ll","Mathematics","M K kanyal"},
			  		  {"C Programming - ll","C Programming: A Modern Approach","K. N. King"},
		};
		String column[]={"Subject","Book Name","Author"};
		JLabel label16 = new JLabel("Subject");
		frame7.getContentPane().add(label16);
		label16.setBounds(200,103,200,200);
		JLabel label17 = new JLabel("Book Name");
		frame7.getContentPane().add(label17);
		label17.setBounds(458,103,200,200);
		JLabel label18 = new JLabel("Author");
		frame7.getContentPane().add(label18);
		label18.setBounds(750,103,200,200);
		JLabel label19 = new JLabel(icon);
		frame7.getContentPane().add(label19);
		label19.setBounds(390,3,200,200);
		JButton button23;
		button23 = new JButton("Back");
		button23.setBounds(430,380,120,20);
		frame7.getContentPane().add(button23);
		JTable table = new JTable(data,column);
	        table.setBounds(100,230,833,250);
		frame7.add(table);
		JMenuBar menuBar7 = new JMenuBar();
		frame7.setJMenuBar(menuBar7);	
		JMenu mnNewMenu7 = new JMenu("Settings");
		menuBar7.add(mnNewMenu7);		
		JMenuItem mntmNewMenuItem7 = new JMenuItem("Log Out");
		mnNewMenu7.add(mntmNewMenuItem7);

		JFrame frame8 = new JFrame();
		frame8.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame8.setBounds(100,100,1000,500);
		Container c8 = frame8.getContentPane();
		c8.setLayout(null);
		c8.setBackground(Color.WHITE);
		frame8.setTitle("ASY Engineering Guide");	
		String data2[][]={         {"Signals and Systems","Signals and Systems"," S. Palani"},    
                          		   {"MCA","The 8051 Microcontroller and Embedded Systems: Using Assembly and C","MAZIDI "},                         
			  		   {"Python Programming ","Learn Python 3 The Hard Way","Zed A. Shaw"},
			  		   {"Data Communication and Computer Network","Data communications","William stallings"},
			  		   {"Control system engineering","Control systems","NAGRATH & GOPAL"},
			  		   {"AEC","Analog electronics circuit","R. S. SEDHA"},

		};
		String column2[]={"Subject","Book Name","Author"};
		JLabel label20 = new JLabel("Subject");
		frame8.getContentPane().add(label20);
		label20.setBounds(200,103,200,200);
		JLabel label21 = new JLabel("Book Name");
		frame8.getContentPane().add(label21);
		label21.setBounds(458,103,200,200);
		JLabel label22 = new JLabel("Author");
		frame8.getContentPane().add(label22);
		label22.setBounds(750,103,200,200);
		JLabel label23 = new JLabel(icon);
		frame8.getContentPane().add(label23);
		label23.setBounds(390,3,200,200);
		JButton button24;
		button24 = new JButton("Back");
		button24.setBounds(430,380,120,20);
		frame8.getContentPane().add(button24);
		JTable table2 = new JTable(data2,column2);
	        table2.setBounds(100,230,833,250);
		frame8.add(table2);
		JMenuBar menuBar8 = new JMenuBar();
		frame8.setJMenuBar(menuBar8);	
		JMenu mnNewMenu8 = new JMenu("Settings");
		menuBar8.add(mnNewMenu8);		
		JMenuItem mntmNewMenuItem8 = new JMenuItem("Log Out");
		mnNewMenu8.add(mntmNewMenuItem8);

		JFrame frame9 = new JFrame();
		frame9.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame9.setBounds(100,100,1000,500);
		Container c9 = frame9.getContentPane();
		c9.setLayout(null);
		c9.setBackground(Color.WHITE);
		frame9.setTitle("ASY Engineering Guide");
		String data3[][]={         {"DSP","Fundamentals of Signals and Systems","  M J. Roberts"},    
                          {"EMAG"," Principles of Electromagnetics ","Matthew N. OSadiku"},                         
			  {"PE ","Power Electronics","Dr. P.S.Bimbhra"},
			  {"Electrical Machines","Electric Machines"," Kothari D P"},
			  {"Data Science using Python","Python for Data Science For Dummies"," John Mueller and Luca Massaron"},	
		};
		String column3[]={"Subject","Book Name","Author"};
		JLabel label24 = new JLabel("Subject");
		frame9.getContentPane().add(label24);
		label24.setBounds(200,103,200,200);
		JLabel label25 = new JLabel("Book Name");
		frame9.getContentPane().add(label25);
		label25.setBounds(458,103,200,200);
		JLabel label26 = new JLabel("Author");
		frame9.getContentPane().add(label26);
		label26.setBounds(750,103,200,200);
		JLabel label27 = new JLabel(icon);
		frame9.getContentPane().add(label27);
		label27.setBounds(390,3,200,200);
		JButton button25;
		button25 = new JButton("Back");
		button25.setBounds(430,380,120,20);
		frame9.getContentPane().add(button25);
		JTable table3 = new JTable(data3,column3);
	        table3.setBounds(100,230,833,250);
		frame9.add(table3);
		JMenuBar menuBar9 = new JMenuBar();
		frame9.setJMenuBar(menuBar9);	
		JMenu mnNewMenu9 = new JMenu("Settings");
		menuBar9.add(mnNewMenu9);		
		JMenuItem mntmNewMenuItem9 = new JMenuItem("Log Out");
		mnNewMenu9.add(mntmNewMenuItem9);

		JFrame frame11 = new JFrame();
		frame11.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame11.setBounds(100,100,1000,500);
		Container c11 = frame11.getContentPane();
		c11.setLayout(null);
		c11.setBackground(Color.WHITE);
		frame11.setTitle("ASY Engineering Guide");		
		String data4[][]={         {"OOP Using C++","Introduction to Object oriented programming in C++"," Robert Lafore"},    
                          {"Data Structure Using C","data structures and C programming","James Aspnes"},    
                          {"Java Programming ","Java: A Beginner’s Guide ","Herbert Schildt"},
			  {"Microprocessors","Microprocessor book","Amesh gaonkar"},
			  {"Data Communication and Computer Network","data communications","william stallings"},
			  {"C Programming - ll","C Programming: A Modern Approach","K. N. King"},
		};
		String column4[]={"Subject","Book Name","Author"};
		JLabel label28 = new JLabel("Subject");
		frame11.getContentPane().add(label28);
		label28.setBounds(200,103,200,200);
		JLabel label29 = new JLabel("Book Name");
		frame11.getContentPane().add(label29);
		label29.setBounds(458,103,200,200);
		JLabel label30 = new JLabel("Author");
		frame11.getContentPane().add(label30);
		label30.setBounds(750,103,200,200);
		JLabel label31 = new JLabel(icon);
		frame11.getContentPane().add(label31);
		label31.setBounds(390,3,200,200);
		JButton button26;
		button26 = new JButton("Back");
		button26.setBounds(430,380,120,20);
		frame11.getContentPane().add(button26);
		JTable table4 = new JTable(data4,column4);
	        table4.setBounds(100,230,833,250);
		frame11.add(table4);
		JMenuBar menuBar11 = new JMenuBar();
		frame11.setJMenuBar(menuBar11);	
		JMenu mnNewMenu11 = new JMenu("Settings");
		menuBar11.add(mnNewMenu11);		
		JMenuItem mntmNewMenuItem11 = new JMenuItem("Log Out");
		mnNewMenu11.add(mntmNewMenuItem11);

		JFrame frame12 = new JFrame();
		frame12.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame12.setBounds(100,100,1000,500);
		Container c12 = frame12.getContentPane();
		c12.setLayout(null);
		c12.setBackground(Color.WHITE);
		frame12.setTitle("ASY Engineering Guide");		
		String data5[][]={         {"Theory of Cs ","Theory of Computer Science"," K.l.p mishra and n. chandrasekaran "},    
                          {"Database Management System"," Dbms  ","Rajiv Chopra "},                         			
			  {"Advanced CN","Advanced Computer Networks","Rahul Sharma"},
			  {"Machine Learning","Machine Learning","Andrew ng"},
		};
		String column5[]={"Subject","Book Name","Author"};
		JLabel label32 = new JLabel("Subject");
		frame12.getContentPane().add(label32);
		label32.setBounds(200,103,200,200);
		JLabel label33 = new JLabel("Book Name");
		frame12.getContentPane().add(label33);
		label33.setBounds(458,103,200,200);
		JLabel label34 = new JLabel("Author");
		frame12.getContentPane().add(label34);
		label34.setBounds(750,103,200,200);
		JLabel label35 = new JLabel(icon);
		frame12.getContentPane().add(label35);
		label35.setBounds(390,3,200,200);
		JButton button27;
		button27 = new JButton("Back");
		button27.setBounds(430,380,120,20);
		frame12.getContentPane().add(button27);
		JTable table5 = new JTable(data5,column5);
	        table5.setBounds(100,230,833,250);
		frame12.add(table5);
		JMenuBar menuBar12 = new JMenuBar();
		frame12.setJMenuBar(menuBar12);	
		JMenu mnNewMenu12 = new JMenu("Settings");
		menuBar12.add(mnNewMenu12);		
		JMenuItem mntmNewMenuItem12 = new JMenuItem("Log Out");
		mnNewMenu12.add(mntmNewMenuItem12);

		JFrame frame13 = new JFrame();
		frame13.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame13.setBounds(100,100,1000,500);
		Container c13 = frame13.getContentPane();
		c13.setLayout(null);
		c13.setBackground(Color.WHITE);
		frame13.setTitle("ASY Engineering Guide");
		
		String data9[][]={         {"Digital Signal & Image Processing","Digital Signal and Image Processing ","by Tamal Bose "},    
                          {"Mobile Communication & Computing"," Mobile Communication and Computing","by Dr. G.T. Thampi "},                         			
			  {"Artificial Intelligence & Soft Computing","Artificial Intelligence and Soft Computing for Beginners"," by Anindita Das Bhattacharya  "},
			  {"Mobile App. Development. Tech"," Android Mobile Application Development using Kotlin"," Iyad Abu Doush"},
		};
		String column9[]={"Subject","Book Name","Author"};
		JLabel label48 = new JLabel("Subject");
		frame13.getContentPane().add(label48);
		label48.setBounds(200,103,200,200);
		JLabel label49 = new JLabel("Book Name");
		frame13.getContentPane().add(label49);
		label49.setBounds(458,103,200,200);
		JLabel label50 = new JLabel("Author");
		frame13.getContentPane().add(label50);
		label50.setBounds(750,103,200,200);
		JLabel label51 = new JLabel(icon);
		frame13.getContentPane().add(label51);
		label51.setBounds(390,3,200,200);
		JButton button31;
		button31 = new JButton("Back");
		button31.setBounds(430,380,120,20);
		frame13.getContentPane().add(button31);
		JTable table9 = new JTable(data9,column9);
	        table9.setBounds(100,230,833,250);
		frame13.add(table9);
		JMenuBar menuBar13 = new JMenuBar();
		frame13.setJMenuBar(menuBar13);	
		JMenu mnNewMenu13 = new JMenu("Settings");
		menuBar13.add(mnNewMenu13);		
		JMenuItem mntmNewMenuItem13 = new JMenuItem("Log Out");
		mnNewMenu13.add(mntmNewMenuItem13);

		JFrame frame14 = new JFrame();
		frame14.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame14.setBounds(100,100,1000,500);
		Container c14 = frame14.getContentPane();
		c14.setLayout(null);
		c14.setBackground(Color.WHITE);
		frame14.setTitle("ASY Engineering Guide");		
		String data6[][]={         {"Database Systems","Database Systems"," Hector Garcia-Molina"},    
                          {"Software Engineering"," Clean Code ","Robert C. Martin "},                         
			  {"Engineering Mathematics ","Engineering Mathematics for Semester","C B Gupta"},
			  {"Multimedia Applications","Multimedia Applications book"," Tay vaughan"},
		};
		String column6[]={"Subject","Book Name","Author"};
		JLabel label36 = new JLabel("Subject");
		frame14.getContentPane().add(label36);
		label36.setBounds(200,103,200,200);
		JLabel label37 = new JLabel("Book Name");
		frame14.getContentPane().add(label37);
		label37.setBounds(458,103,200,200);
		JLabel label38 = new JLabel("Author");
		frame14.getContentPane().add(label38);
		label38.setBounds(750,103,200,200);
		JLabel label39 = new JLabel(icon);
		frame14.getContentPane().add(label39);
		label39.setBounds(390,3,200,200);
		JButton button28;
		button28 = new JButton("Back");
		button28.setBounds(430,380,120,20);
		frame14.getContentPane().add(button28);
		JTable table6 = new JTable(data6,column6);
	        table6.setBounds(100,230,833,250);
		frame14.add(table6);
		JMenuBar menuBar14 = new JMenuBar();
		frame14.setJMenuBar(menuBar14);	
		JMenu mnNewMenu14 = new JMenu("Settings");
		menuBar14.add(mnNewMenu14);		
		JMenuItem mntmNewMenuItem14 = new JMenuItem("Log Out");
		mnNewMenu14.add(mntmNewMenuItem14);

		JFrame frame15 = new JFrame();
		frame15.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame15.setBounds(100,100,1000,500);
		Container c15 = frame15.getContentPane();
		c15.setLayout(null);
		c15.setBackground(Color.WHITE);
		frame15.setTitle("ASY Engineering Guide");		
		String data7[][]={         {"Web Tech ","Web Technology","M. Srinivasan"},    
                          {"OS"," Operating Systems  ","Abraham Silberschatz"},                         			
			  {"Image Processing","Image Processing Guide","Rafael C. Gonza Lez and Richard E. Woods "},
			  {"Data Warehousing & Mining","Data Mining and Data Warehousing"," Parteek Bhatia"},
		};
		String column7[]={"Subject","Book Name","Author"};
		JLabel label40 = new JLabel("Subject");
		frame15.getContentPane().add(label40);
		label40.setBounds(200,103,200,200);
		JLabel label41 = new JLabel("Book Name");
		frame15.getContentPane().add(label41);
		label41.setBounds(458,103,200,200);
		JLabel label42 = new JLabel("Author");
		frame15.getContentPane().add(label42);
		label42.setBounds(750,103,200,200);
		JLabel label43 = new JLabel(icon);
		frame15.getContentPane().add(label43);
		label43.setBounds(390,3,200,200);
		JButton button29;
		button29 = new JButton("Back");
		button29.setBounds(430,380,120,20);
		frame15.getContentPane().add(button29);
		JTable table7 = new JTable(data7,column7);
	        table7.setBounds(100,230,833,250);
		frame15.add(table7);
		JMenuBar menuBar15 = new JMenuBar();
		frame15.setJMenuBar(menuBar15);	
		JMenu mnNewMenu15 = new JMenu("Settings");
		menuBar15.add(mnNewMenu15);		
		JMenuItem mntmNewMenuItem15 = new JMenuItem("Log Out");
		mnNewMenu15.add(mntmNewMenuItem15);

		JFrame frame16 = new JFrame();
		frame16.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame16.setBounds(100,100,1000,500);
		Container c16 = frame16.getContentPane();
		c16.setLayout(null);
		c16.setBackground(Color.WHITE);
		frame16.setTitle("ASY Engineering Guide");
		
		String data8[][]={         {"Cloud Computing ","Cloud Computing: Concepts, Technology & Architecture ","H. joseph"},    
                          {"Cryptography and Network Security"," Cryptography and Network Security ","William Stallings"},                         			
			  {"Big Data Analytics","Big Data Analytics Guide"," Venkat Ankam "},
			  {"Internet of Everything","Internet of Everything"," Laura DeNardis"},
		};
		String column8[]={"Subject","Book Name","Author"};
		JLabel label44 = new JLabel("Subject");
		frame16.getContentPane().add(label44);
		label44.setBounds(200,103,200,200);
		JLabel label45 = new JLabel("Book Name");
		frame16.getContentPane().add(label45);
		label45.setBounds(458,103,200,200);
		JLabel label46 = new JLabel("Author");
		frame16.getContentPane().add(label46);
		label46.setBounds(750,103,200,200);
		JLabel label47 = new JLabel(icon);
		frame16.getContentPane().add(label47);
		label47.setBounds(390,3,200,200);
		JButton button30;
		button30 = new JButton("Back");
		button30.setBounds(430,380,120,20);
		frame16.getContentPane().add(button30);
		JTable table8 = new JTable(data8,column8);
	        table8.setBounds(100,230,833,250);
		frame16.add(table8);
		JMenuBar menuBar16 = new JMenuBar();
		frame16.setJMenuBar(menuBar16);	
		JMenu mnNewMenu16 = new JMenu("Settings");
		menuBar16.add(mnNewMenu16);		
		JMenuItem mntmNewMenuItem16 = new JMenuItem("Log Out");
		mnNewMenu16.add(mntmNewMenuItem16);

		JFrame frame17 = new JFrame();
		frame17.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame17.setBounds(100,100,1000,500);
		Container c17 = frame17.getContentPane();
		c17.setLayout(null);
		c17.setBackground(Color.WHITE);
		frame17.setTitle("ASY Engineering Guide");
		
		String data11[][]={         {"Antennas and Microwave Engineering","Antennas & Microwave Engineering  ","by M. Manju U. A. Bakshi"},    
                          {"Optical Communication"," Optical Fiber Communications: Principles and Practice","by Dr. G.V. Bhusan "},                         			
			  {"Embedded and Real Time Systems","Embedded / Real-Time Systems: Concepts &  Design "," by Dr. K.V.K Prasad   "},
			  {"Wireless Sensor Networks"," Wireless Sensor Networks: From Theory to Applications"," by Ibrahiem M. M. El Emary "},
		};
		String column11[]={"Subject","Book Name","Author"};
		JLabel label56 = new JLabel("Subject");
		frame17.getContentPane().add(label56);
		label56.setBounds(200,103,200,200);
		JLabel label57 = new JLabel("Book Name");
		frame17.getContentPane().add(label57);
		label57.setBounds(458,103,200,200);
		JLabel label58 = new JLabel("Author");
		frame17.getContentPane().add(label58);
		label58.setBounds(750,103,200,200);
		JLabel label59 = new JLabel(icon);
		frame17.getContentPane().add(label59);
		label59.setBounds(390,3,200,200);
		JButton button33;
		button33 = new JButton("Back");
		button33.setBounds(430,380,120,20);
		frame17.getContentPane().add(button33);
		JTable table11 = new JTable(data11,column11);
	        table11.setBounds(100,230,833,250);
		frame17.add(table11);
		JMenuBar menuBar17 = new JMenuBar();
		frame17.setJMenuBar(menuBar17);	
		JMenu mnNewMenu17 = new JMenu("Settings");
		menuBar17.add(mnNewMenu17);		
		JMenuItem mntmNewMenuItem17 = new JMenuItem("Log Out");
		mnNewMenu17.add(mntmNewMenuItem17);

		button.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame.setVisible(false);
				frame2.setVisible(true); 
			}
		});		
		button2.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame2.setVisible(false);
				frame3.setVisible(true);
			}
		});
		button3.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame2.setVisible(false);
				frame4.setVisible(true);
			}
		});
		button4.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame2.setVisible(false);
				frame6.setVisible(true);
			}
		});
		button10.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame3.setVisible(false);
				frame2.setVisible(true);
			}
		});
		button17.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame4.setVisible(false);
				frame2.setVisible(true);
			}
		});
		button22.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame6.setVisible(false);
				frame2.setVisible(true);
			}
		});
		button5.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame3.setVisible(false);
				frame7.setVisible(true);
			}
		});
		button13.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame4.setVisible(false);
				frame7.setVisible(true);
			}
		});
		button14.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame4.setVisible(false);
				frame11.setVisible(true);
			}
		});
		button15.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame4.setVisible(false);
				frame12.setVisible(true);
			}
		});
		button16.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame4.setVisible(false);
				frame13.setVisible(true);
			}
		});
		button19.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame6.setVisible(false);
				frame14.setVisible(true);
			}
		});
		button20.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame6.setVisible(false);
				frame15.setVisible(true);
			}
		});
		button21.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame6.setVisible(false);
				frame16.setVisible(true);
			}
		});
		button6.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame3.setVisible(false);
				frame8.setVisible(true);
			}
		});
		button7.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame3.setVisible(false);
				frame9.setVisible(true);
			}
		});
		button8.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame3.setVisible(false);
				frame17.setVisible(true);
			}
		});
		button24.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame8.setVisible(false);
				frame2.setVisible(true);
			}
		});
		button25.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame9.setVisible(false);
				frame2.setVisible(true);
			}
		});
		button26.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame11.setVisible(false);
				frame2.setVisible(true);
			}
		});
		button27.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame12.setVisible(false);
				frame2.setVisible(true);
			}
		});
		button28.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame14.setVisible(false);
				frame2.setVisible(true);
			}
		});
		button29.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame15.setVisible(false);
				frame2.setVisible(true);
			}
		});
		button30.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame16.setVisible(false);
				frame2.setVisible(true);
			}
		});
		button31.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame13.setVisible(false);
				frame2.setVisible(true);
			}
		});
		button33.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame17.setVisible(false);
				frame2.setVisible(true);
			}
		});
		button18.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame6.setVisible(false);
				frame7.setVisible(true);
			}
		});
		button23.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame7.setVisible(false);
				frame2.setVisible(true);
			}
		});
		mntmNewMenuItem2.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame2.setVisible(false);
				frame.setVisible(true);
			}
		});
		mntmNewMenuItem3.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame3.setVisible(false);
				frame.setVisible(true);
			}
		});
		mntmNewMenuItem4.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame4.setVisible(false);
				frame.setVisible(true);
			}
		});
		mntmNewMenuItem6.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame6.setVisible(false);
				frame.setVisible(true);
			}
		});
		mntmNewMenuItem7.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame7.setVisible(false);
				frame.setVisible(true);
			}
		});
		mntmNewMenuItem8.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame8.setVisible(false);
				frame.setVisible(true);
			}
		});
		mntmNewMenuItem9.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame9.setVisible(false);
				frame.setVisible(true);
			}
		});
		mntmNewMenuItem11.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame11.setVisible(false);
				frame.setVisible(true);
			}
		});
		mntmNewMenuItem12.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame12.setVisible(false);
				frame.setVisible(true);
			}
		});
		mntmNewMenuItem13.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame13.setVisible(false);
				frame.setVisible(true);
			}
		});
		mntmNewMenuItem14.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame14.setVisible(false);
				frame.setVisible(true);
			}
		});
		mntmNewMenuItem15.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame15.setVisible(false);
				frame.setVisible(true);
			}
		});
		mntmNewMenuItem16.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame16.setVisible(false);
				frame.setVisible(true);
			}
		});
		mntmNewMenuItem17.addActionListener(new ActionListener(){
			public void actionPerformed(ActionEvent arg0){
				frame17.setVisible(false);
				frame.setVisible(true);
			}
		});
	}
}
