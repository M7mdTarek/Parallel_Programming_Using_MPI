# Problem1 Statement:
- develop a parallel program that outputs max number in a given array using Master-Slave paradigm where :
- ## Master:
    1. Reads size of array.
    2. Reads elements inside array.
    3. Distributes the work among slaves processes:

        • Sends size of the array.

        • Sends the assigned partition of the array.

- After each slave finishes its work, master process receives max number and its index from each process.
- Then master computes the max number from max numbers returned from each slave.
- Output the final max number and its index in the original array to user.
## Slaves each one will:
- Receives size of the array.
- Receives the portion of the array.
- Calculates max number.
- Sends max number and its index back to master process.
#### Note: Size of array may not be divisible by number of processes. So, you should handle this case.
## Screenshot
![problem1](https://user-images.githubusercontent.com/100175518/226146212-76e18c04-347e-45ab-937a-d7d5263b0a8d.png)

# Problem2 Statement :
develop a parallel program that calculate matrix multiplication .

- Matrices’ dimensions and values are taken as an input. 
- Multiply the two matrices together then print the result. 
- implement this program in two modes.
  1. First mode reads the input from the console 
  2. the second one reads the input from a file.
#### Note : useing dynamic allocation.
## Screenshot
![problem2_file](https://user-images.githubusercontent.com/100175518/226146281-866c760f-9c91-4e6b-b768-285b687f9b52.png)
![problem2_input](https://user-images.githubusercontent.com/100175518/226146282-00e4fa4a-40d1-4253-8431-c1fac5694c38.png)

