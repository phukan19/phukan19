- 👋 Hi, I’m @phukan19
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
phukan19/phukan19 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
1 import turtle
2 from random import randint, choice
3
4 #set up screen
5 width=700
6 height=500
7 S=turtle.Screen()
8
9 S.setup(with, height)
10 S.bgcolor("black")
11 S.title("Fireworks")
12
13 turtle.mainloop()
14 colors=["red", "green", "yellow, "gold", "pink", "cyan", "white", "orange", "violet", "coral"]
15
16 class Fireworks:
17      def___init__(self, radius):
18           self.T=turtle.Pen()
19           self.T.speed(0)
20           self.T.color(choice(colors))
21           self.T.hideturtle()
22           self.T.up()
23           self.T.setposition(randint(-250, 250), randint(0, 200)
24           self.T.radius=radius
25       def update(self):
26           self.T.forward(self.radius)
27           self.T.backward(self.radius)
29           self.T.left(10)
30
31       def clean(self):
32           self.T.clear()
33           self.T.color(choice(colors))
34           self.t.up()
35           self.T.setposition(randint(-250, 250), randint(0,200))
36           self.T.down()
37     
38 #fireworks
39 T1=Fireworks(randint(10,100))
40 T2=Fireworks(randint(10,100))
41 T3=Fireworks(randint(10,100))
42 T4=Fireworks(randint(10,100))
43 T5=Fireworks(randint(10,100))
44
45 T=turtle.pen
46 T.sety(-150)
47 T.color("gold")
48 T.write("HAPPY NEW YEAR TO MY DEAR ANJIMA!")
49 while True:
50       for i in range(36):
51            T1.update()
52 	      T2.update()
53            T3.update()
54           T4.update()
55          T5.update()
56
57       T1.clean()
58       T2.clean()
59       T3.clean()
60       T4.clean()
61       T5.clean()
62
63 turtle.mainloop()
