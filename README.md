<h1 align="center"> Hey! I am Lucas. </h1>
<div> 
  <p> ➤ Looking for an opportunity in the area.  </p> 
<p> ➤ I love new challenges. </p>
<p> ➤ Python ❤️ </p>
<p> ➤ Trying to improve myself more and more. </p>
</div>
<h1>  My Github Stats </h1>
  <p align="center"><img src="https://github-readme-streak-stats.herokuapp.com?user=Lucas836-hub&theme=github-dark&date_format=M%20j%5B%2C%20Y%5D"/></p>
  <p align="center"><img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Lucas836-hub&theme=github_dark"/></p>
<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Lucas836-hub&theme=github_dark"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Lucas836-hub&theme=github_dark"/>
</div>
<p align="center"> 
</p>

```python3
from time import sleep
from random import randint
import platform
import os

class main():
	def __init__(self):
		self.about_me()
		self.finish()
		self.error()
	def about_me(self):
		ale=randint(0,7)
		print("\n\nABOUT ME".center(50))
		print(f"\033[9{ale}m just curious about programming, trying to learn and change things for the better. \033[m".center(50))
		sleep(3)

	def finish(self):
		for c  in range(0,10):
			self.limp()
			ale=randint(0,7)
			print("\n\n\n\n\n")
			print(f"\033[9{ale}m:)  see you soon.\033[m".center(50))
			sleep(0.5)

	def plataforma(self):
		return platform.system()

	def limp(self):
		s=self.plataforma()
		
		if s == "Linux" :
			os.system("clear")
			
		if s == "Windows" :
			os.system("cls")
			
		if s == "Darwin" :
			os.system("clear")
	def error(self):
		self.limp()
		print("""\033[31m
			    ____ ___   ___  ____  
			    |    |  |  |  | |   |   | | |
			    |--- |__|  |__| |   |   | | |
			    |___ |   \ |  \ |___|   . . .
		\033[m""".center(100))

		sleep(2)

		for c in range(0,105,5):
			self.limp()
			print("""\033[31m
			     ____ ___   ___  ____  
			     |    |  |  |  | |   |   | | |
			     |--- |__|  |__| |   |   | | |
			     |___ |   \ |  \ |___|   . . .
		\033[m""".center(100))
			print("\033[92mHackeando o FBI")
			print("-"*c,f"-> {c}%")
			sleep(0.5)
		print("\nFBI hackeado :)")
		sleep(3)
		for i in range(0,100):
			print(f"\033[92m{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}{randint(0,1)}"*100)
			sleep(0.1)
		self.limp()
		print('''\033[31m
				       uuuuuuu
				     uu$$$$$$$$$$$uu
				  uu$$$$$$$$$$$$$$$$$uu
				 u$$$$$$$$$$$$$$$$$$$$$u
				u$$$$$$$$$$$$$$$$$$$$$$$u
			       u$$$$$$$$$$$$$$$$$$$$$$$$$u
			       u$$$$$$$$$$$$$$$$$$$$$$$$$u
			       u$$$$$$"   "$$$"   "$$$$$$u
			       "$$$$"      u$u       $$$$"
				$$$u       u$u       u$$$
				$$$u      u$$$u      u$$$
				 "$$$$uu$$$   $$$uu$$$$"
				  "$$$$$$$"   "$$$$$$$"
				    u$$$$$$$u$$$$$$$u
				     u$"$"$"$"$"$"$u
			  uuu        $$u$ $ $ $ $u$$       uuu
			 u$$$$        $$$$$u$u$u$$$       u$$$$
			  $$$$$uu      "$$$$$$$$$"     uu$$$$$$
			u$$$$$$$$$$$uu    """""    uuuu$$$$$$$$$$
			$$$$"""$$$$$$$$$$uuu   uu$$$$$$$$$"""$$$"
			 """      ""$$$$$$$$$$$uu ""$"""
				   uuuu ""$$$$$$$$$$uuu
			  u$$$uuu$$$$$$$$$uu ""$$$$$$$$$$$uuu$$$
			  $$$$$$$$$$""""           ""$$$$$$$$$$$"
			   "$$$$$"                      ""$$$$""
			     $$$"                         $$$$"
		\033[m''')
		sleep(2)
		self.limp()

if __name__ == "__main__":
	main()
