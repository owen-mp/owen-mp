```py
class Kae:
    """About my life :3"""
    @property
    def life(self):
        age = 15
        name = "Hassan"
        langs = ["English", "Hindi"]
        games = ["Valorant", "Fortnite", "Minecraft"]

        return age, name, langs, games

    @property
    def setup(self):
        software = ["PyCharm", "Visual Studio Code"]
        specifications = {
            "peripherals": {
                "monitor": "AOC 24GI5N 180hz",
                "keyboard": ["Redragon k617 fizz 60%", "MageGee 65%"],
                "mouse": "katar pro",
            },
            "build": {
                "CPU": "i5 12400f",
                "GPU": "RTX 3060 12gb Vram",
                "RAM": "XPG Adata 16gb RAM"
            }
        }

        return software, specifications
    
    @property
    def interests(self):
        interested = ["Reverse Engineering", "Networking"]
        working = ["Navium", "FunCaptcha Solver"]

        return interested, working
```
