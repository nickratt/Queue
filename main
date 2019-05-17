#include <iostream>
#include <cstdlib>

using namespace std;

int queue[30], frontindx = 0, backindx = -1;  //global variable

void push(int x) //Inserts value to the queue
{
  backindx++; //increments the back index;
  queue[backindx]=x; //sets the index of the array of the queue to x;
  
  
}

void pop() //deletes the first element added
{
  queue[frontindx] = 0; // sets the index of the array in the queue to 0
  frontindx++; //increments the front index
  

}

bool empty() //checks to see if queue is empty
{
 if (backindx < frontindx){
   return true;
 } else{
   return false;
 }
}

int front() // returns the front number in the queue
{
  return queue[frontindx];
}

int main()
{
  push(5);
  push(4);
  pop();
  pop();
  push(10);
  push(7);

  if (!empty()) cout << front() << endl; //if stack is empty, program will not look for value
}
