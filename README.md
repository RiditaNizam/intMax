# intMax
CodingBat Java Warmup-1 Question

Given three int values, a b c, return the largest.

public int intMax(int a, int b, int c) {
  if(a > b && a > c){
    return a;
  }
  
  else if(b > a && b > c){
    return b;
  }
  
  else if(c > a && c > b){
    return c;
  }
  
  return 0;
  
}
