###Author: Adolfo Lara
###Purpose: Output list of indeces.


#Ideal way the program would work -  
#Input: coordinates
    #enter A01
    #enter H05
firstindex = input("Please enter 1st index: ")
firstindex = firstindex.upper()
##Ask total number of samples as asking for last index is more difficult. 
totalsamples = input("Please enter total number of samples: ")


#Data we have:
indeces = [
"A01", "B01", "C01", "D01", "E01", "F01", "G01", "H01",
"A02", "B02", "C02", "D02", "E02", "F02", "G02", "H02",
"A03", "B03", "C03", "D03", "E03", "F03", "G03", "H03",
"A04", "B04", "C04", "D04", "E04", "F04", "G04", "H04",
"A05", "B05", "C05", "D05", "E05", "F05", "G05", "H05",
"A06", "B06", "C06", "D06", "E06", "F06", "G06", "H06",
"A07", "B07", "C07", "D07", "E07", "F07", "G07", "H07",
"A08", "B08", "C08", "D08", "E08", "F08", "G08", "H08",
"A09", "B09", "C09", "D09", "E09", "F09", "G09", "H09",
"A10", "B10", "C10", "D10", "E10", "F10", "G10", "H10",
"A11", "B11", "C11", "D11", "E11", "F11", "G11", "H11",
"A12", "B12", "C12", "D12", "E12", "F12", "G12", "H12",
"A01", "B01", "C01", "D01", "E01", "F01", "G01", "H01",
"A02", "B02", "C02", "D02", "E02", "F02", "G02", "H02",
"A03", "B03", "C03", "D03", "E03", "F03", "G03", "H03",
"A04", "B04", "C04", "D04", "E04", "F04", "G04", "H04",
"A05", "B05", "C05", "D05", "E05", "F05", "G05", "H05",
"A06", "B06", "C06", "D06", "E06", "F06", "G06", "H06",
"A07", "B07", "C07", "D07", "E07", "F07", "G07", "H07",
"A08", "B08", "C08", "D08", "E08", "F08", "G08", "H08",
"A09", "B09", "C09", "D09", "E09", "F09", "G09", "H09",
"A10", "B10", "C10", "D10", "E10", "F10", "G10", "H10",
"A11", "B11", "C11", "D11", "E11", "F11", "G11", "H11",
"A12", "B12", "C12", "D12", "E12", "F12", "G12", "H12"
]

#middleman : number
    #Turn both A01 and H05 to numbers - how?
    #Google search: "given an element on a list, get its position" 
        #Website: https://stackoverflow.com/questions/176918/finding-the-index-of-an-item-in-a-list
        #Example:
        #["foo", "bar", "baz"].index("bar")
firstindexvalue = indeces.index(firstindex)
###Key: add first index to total samples and this gives you last index
lastindexvalue = firstindexvalue + int(totalsamples)

#fetch in list with numbers
#translate to coordinates
#output coordiantes
x = firstindexvalue
y = lastindexvalue
for i in indeces:
    if x < y: 
        print(indeces[x])
        x = x + 1

#fetch items in list with numbers
#print(indeces[firstindexvalue:lastindexvalue])

#i = firstindexvalue
#for i in lastindexvalue:
#    print(indeces[i])

#for i in indeces:
#    print(i)

#print(firstindexvalue,lastindexvalue)

#for i in indeces:
#    print(indeces[1:3])

#Example Input: A01 - H02
#Enter first index:
#Enter last index:

#Output:
#A01
#B01
#C01
#D01
#E01
#F01
#G01
#H01

#A01 = 1
#B01 = 2
#C01 = 3
#D01 = 4
#E01 = 5 
#F01 = 6 
#G01 = 7
#H01 = 8

#Ideal way the program would work - 
#Input: coordinates
    #enter A01
    #enter H05
#middleman : number
    #Turn both A01 and H05 to numbers - how?
    #Google search: "given an element on a list, get its position" 
        #Website: https://stackoverflow.com/questions/176918/finding-the-index-of-an-item-in-a-list
        #Example:
        #["foo", "bar", "baz"].index("bar")
#fetch in list with numbers
#translate to coordinates
#output coordiantes

#Trying to output the firdst elelment of a dictionary but dictionaries are not otrdered, so a list would be bettter to use. 
#print(indeces{0})
