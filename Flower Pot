from typing import List

def plant(flowerbed: List[int], n: int) -> bool:
  count = 0
  length = len(flowerbed)
  
  for i in range(length):
    if flowerbed[i] == 0:
      before_pot = i == 0 or flowerbed[i - 1] == 0
      after_pot = i == length - 1 or flowerbed[i + 1] == 0
      
      if before_pot and after_pot:
        flowerbed[i] = 1
        count +=1
        
  if count >= n:
    return True
  else:
    return False
  
   
print(plant([1,0,0,0,1], 1))
