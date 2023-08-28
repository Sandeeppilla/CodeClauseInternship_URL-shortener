# CodeClauseInternship_URL-shortener
import pyshorteners
link=input("Enter a link:")
shortener=pyshorteners.Shortener()
x=shortener.tinyurl.short(link)
print(x)
