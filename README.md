public int task(String n) {

char max = '0';

for(int i = 0; i < n.length(); i++) {
     if(n[i] > max) {
       max = n[i];
     }
    
}

return max - '0';

}
