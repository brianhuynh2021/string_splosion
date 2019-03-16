# string_splosion
Given a non-empty string like "Code" return a string like "CCoCodCode". 
string_splosion('Code') → 'CCoCodCode' 
string_splosion('abc') → 'aababc' 
string_splosion('ab') → 'aab'

#Code 1:
def string_Splosion(str):
  result = str
  for i in reversed(range(len(str))):
    result = str[:i] + result
  return result
#Code 2:
def string_Splosion(str):
  result = ""
  for in in range(len(str):
    result = result + str[:i + 1]
  return result.
    
