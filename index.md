# Jett Pennington's Blog

### My First Week
My First Week has been quite interesting. I appreciate that this first week has been mostly review for me as my personal life has taken up more time than expected for me. All around quite the fun week and it was about what I expected being mostly set-up for things to come.

### Things to Learn
I am Looking forward to back end development quite a bit as its the part i have historically liked and i can't wait to do more

### Something Neat About Me
Something you're not likely to know about me without reading this is that I'm bilingual and speak both Spanish and english. Así pude escribirme cosas en español e inglés.


### Code Snippet

Some old python code that i made to quckly come up with speeds for a dnd charcter who was from a far away 

```Python

baseUnit = input("Unit you want to convert from(hst/mph): ")
finalUnit = input("Unit you want to convert to(hst/mph): ")
numberInput = input("Number being converted: ")

numberInput = int(numberInput)

#to covert to hst you mutiply by 0.03

def convert(num):
    if baseUnit == "hst":
        if finalUnit == "hst":
            return num
        if finalUnit == "mph":
            return num * 0.03
    if baseUnit == "mph":
        if finalUnit == "mph":
            return num
        if finalUnit == "hst":
            return num / 0.03


print(convert(numberInput))

```