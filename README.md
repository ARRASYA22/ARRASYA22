  public static void main(String[] args) {
       int energi;
    int ketinggian;
    int kecepatan;
    String merek;
    void terbang(){
     energi--;
        if(energi > 10){
           ketinggian++;
            System.out.println("Dorne terbang...");
        } else {
            System.out.println("Energi lemah: Drone nggak bisa terbang");
        }
