# Encrypted_File_Detector
A program I wrote for my final year project 

import os
import sys
import math
import collections
import operator

print Please select one of the following options 
print [1] for entropy scan
print [2] for registry artefact analysis

person = input()

if person == 1
def combine_dicts(a, b, op=operator.add):
    return dict(a.items() + b.items() +
        [(k, op(a[k], b[k])) for k in set(b) & set(a)])

freqList = []

f = open("100", "rb")
byte = []
counter = collections.Counter({'100':0})

while True:

    byteArr = map(ord, f.read(4096))
    if byteArr:
        byte = byteArr
        #print byte
        temp = collections.Counter(byte)
        #combine_dicts(temp, counter, operator.add)
        counter = temp + counter
        #print counter
    else:
        break
f.close()
#fileSize = len(byte)
fileSize = sum(counter.values())
print fileSize
counter = collections.Counter(counter)
print counter   
#print byte
#print "file sieze", len(byte)
#print counter
    
for key in counter:
    freqList.append(float(counter[key]) / fileSize) 

ent = 0.0 
for freq in freqList:
    if freq > 0:
        ent = ent + freq * math.log(freq, 2) 
ent = -ent 
print 'Shannon entropy (min bits per byte-character):' 
print ent

if person == 2
    Vol = [TrueCryptVolumeF, TrueCryptVolumeI, TrueCryptVolumeJ, TrueCryptVolumeK, TrueCryptVolumeL, TrueCryptVolumeM, TrueCryptVolumeN, TrueCryptVolumeO, TrueCryptVolumeP, TrueCryptVolumeQ, TrueCryptVolumeR, TrueCryptVolumeS, TrueCryptVolumeT, TrueCryptVolumeU, TrueCryptVolumeV, TrueCryptVolumeW, TrueCryptVolumeX, TrueCryptVolumeY, TrueCryptVolumeZ]
    
    reg = []

    key = _winreg.OpenKey(_winreg.HKEY_LOCAL_MACHINE, r'SYSTEMMountedDevices', 0, _winreg.KEY_READ)

    for i in xrange(0, _winreg.QueryInfoKey(key)[1]-1)
        reg.append(_winreg.EnumValue(key, i))
    
    for i in range(19)

        m = filter(lambda x Vol[i] in x, reg)
        if m
        
            print TRUECRYPTVOLUME HAS BEEN MOUNTED ON THIS SYSTEM n, m 
