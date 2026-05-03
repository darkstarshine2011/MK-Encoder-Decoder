#github.com/darkstarshine2011/MK-Encoder-Decoder
#MK encoder by darkstarshine2011 for Nyxilion(Mohammad MK)

import sys

CharacterLocation = input("      Character Location\n</>>")
CharFile = open(CharacterLocation,"rt")
CharMap = CharFile.read()
Command = None
try:
    while True:

        Command = int(input("""            
        [1] Encode
        [2] Decode
        [3] change CharMap
        [4] Quit
        
</>>"""))
        if Command not in [1, 2, 3, 4]:
            raise ValueError("Invalid Command")

        if Command == 1:
            Path = input("\n\n        File Path\n</>>")
            File = open(Path, "rt")
            NotEncrypted = File.read()
            Encrypted = ""
            for i in NotEncrypted:
                if i in CharMap:
                    print(CharMap[-(CharMap.find(i))])
                    Encrypted += CharMap[-(CharMap.find(i))]
                else:
                    Encrypted += i
            File.close()
            File = open("Encrypted.MK", "wt")
            File.write(Encrypted)
            File.close()
            print("File encrypted in Encrypted.MK")

        if Command == 2:
            Path = input("\n\n        File Path\n</>>")
            File = open(Path, "rt")
            Encrypted = File.read()
            Decrypted = ""
            for i in Encrypted:
                if i in CharMap:
                    print(CharMap[-(CharMap.find(i))])
                    Decrypted += CharMap[-(CharMap.find(i))]
                else:
                    Decrypted += i
            File.close()
            File = open("Decrypted.MK", "wt")
            File.write(Decrypted)
            File.close()
            print("File decrypted in Decrypted.MK")

        if Command == 3:
            CharacterLocation = input("\n\n        Character Location\n</>>")
            CharFile = open(CharacterLocation, "rt")
            CharMap = CharFile.read()
            print(f"CharMap Changed to {CharMap}")

        if Command == 4:
            print("----QUIT----")
            sys.exit()
except ValueError:
    print("Value Error")
except IndexError:
    print("Index Error")
except KeyboardInterrupt:
    print("Keyboard Interrupt")
except EOFError:
    print("EOF Error")
except FileNotFoundError:
    print("File Not Found")
except NameError:
    print("Name Error")
