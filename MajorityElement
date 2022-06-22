class MajorityElement {
    public static void main(String[] args) {
        
        int duplicateNumbers[] = {2, 8, 7, 2, 2, 5, 2, 3, 1, 2, 2};
        int count = 0;
        int majorityNumber = 0;
        for(int number : duplicateNumbers) {
            
            if (count == 0) {
                majorityNumber = number;
            }
            
            if (number == majorityNumber) {
                count++;
            } else {
                count--;
            }
            
            
        }
        
        System.out.println("The majority element is : "+majorityNumber);
    }
}
