# Training Day1
# Content Of Course
 * Problem Solving Techniques
 * Agile and Scrum
 * Database--SQL Database ---CaseStudy+Assignment+ Coding Challenge
 * C# ---Programming with C# Language----Case study + Assignment+ Coding Challenge

# Algorithm
* Step by step Procedure to solve a problem
    * Searching and Sorting

* Time Complexity -----How much time code takes to execute
    * More time ---->Less Efficient(inversly Proportional)
    * 1+2+3+4+5+6--->21
* Space Complexity---- How much Resources code uses(Memory)

```
                                        Frequency
int arr[]={1,5,2};                       1
int n=arr.length;                        1
int sum=0;                               1
for(int i=0;i<n;i++>){                   4   n+1
    sum=sum+arr[i];                      3    n
}
```
1+1+1+n+1+n---> 2n+4
* Remove all the constants
* Retain the Higher Order
Worst Case---O(n)----> big oh Notation --Upper Bound
Average--Omega Notation---> Average time
Best case----ShortestTime --->Theta notation
```
                                            F
for( int i=0; i<n;i++>)                     n+1
{
    for(int j=0;j<n;j++>){                  n (n+1)       
    cout("*");                              n*n
    }
  cout();                                   n
}
n+1+n(n+1)+n2+n
n2+n
O(n2)---->Exponetial Graph

1 2 3           6 7 8
4 5 6           9 1 2
```
                                   Frequency
for(int i=0; i<n;i++>)              n+1   
                                        
{
    for(int j=0;j<i;j++>)           n(n+1)/2+n
    {
        //statements                n(n+1)/2
    }
    //statements                    n
}
```
O(n2)
i     j     No of times j executed
 0    0          1, +1
 1    0,1        2, +1
 2    0,1,2      3, +1
                 4,

```
for(int i=1;i<n;i=i*2)
{
    //statements
}
```
1st trial  i=1,    1*2    2
2          1*2*2    4     
3          1*2*2*2  8
:
:
K                         2K
Termination Condition----->2K>=n
2K=n
log(2K)=log(n)
klog(2)=log(n)
k=log(n)
O(log n)

```
int z=a+b+d;
result(z);
```
* 4(4)=16

# Algorithm Basics
 * Heuristic Approach/Brute Force Technique
 * Greedy Approach
 * Divide and Concoquer
 * Dynamic programming


 # Pattern matching----given a string str, pattern pattrn, check whether the pattern is presentin the string or not
 str=" DatastructuresSession"
 Pattrn="Session"

 (Pseudocode)
 * store string in some variable
 * store Pattern in some Variable
 * check each character of the pattern with main string if charcter matches, move to the next char
* if entire match is found, exit the loop and print it

#Greedy Approach
 * Choose the optimal solution at each step
 * 1,3,5,6------Largest single digit number---6
 *        ------Largest two digit num----65
 # Activity Scheduling Problem
 Activity1   00-----6:00Pm
 Activity2   3:00----4:00
 Activity3  1:00---2:00
            5:00---7:00
            8:00----9:00
            5:00---9:00
* Sort the Arrays in Ascending Order of the end time
activity            start    end
activity3           1          2
act2                3          4
act1                0           6
act4                5           7
act5                 8          9

# Divide and Conquer
* Take complex problem
* spilt into smaller chunks
* solve them using Known factor
* combine all the result and get the optimal solution
ex:Binary Search, Merge Sort

Item   I1, I2 , I3
Weight 7   5    6
value  80   60  25

capacity=10
I1----7      Values   2pow n
I2---
I3
I1,I2
I1,I3
I2,I3
I,I2,I3

Dynamic Programming---O(n*w)

# Characteristics or Properties of algorithm
 * Definitiness----
 * Finiteness----
 * Input----
 * Output----
 * Effectiveness--

 # Find the Average  marks scored by students in 3 subjects

 Step1: Read Marks m1,m2,m3
 step2:sum=m1+m2+m3
 step3:average=sum/3
 step4:display Average


 # Datastructure
  * Linear----Arrays----Fixed Size, Linked List-->,queue->, Stack->
  int [] numb={1,2,3,4}
  * Non-Linear Datastructure----Tree,Graphs

# Static and Dynamic Structure
```
struct node
{
    int data;
    struct node *next
}
```
# Javascript
* programming Language, --Object oriented 
* HTML----Skeleton for web Page
* CSS-----Cascading Style sheet---to style the web page
* JS---- it makes Web pages interactive

# History
 * Brendan Eich----1995 --He was an employee of netScape
 * when it was intially developed---Live Script----Later changed Javascript
 * Nescape sumbitted Javascript to ECMA(European Computer Manufactures Association)
 * ECMA Script----Standarad that Javascript Follows
  * 1997----ES1
  * 2015---ES6
* Cofee Script, TypeScript----Product Microsoft
* Frameworks----Angular, React, Vue

# Data types and Variables in JS
Keywords for variable Declarion----let, Var, const
# Naming Conventions for variables
 * variable names are Case Sensitive
 * Reserverd Keywords cannot be used
 * letters, digits, underscores are allowed
 * first character of variable should be _, letter , $
* String
* Number
* Boolean
* object
* Array

# Operators
* Addition, Sub,Multiply, Division
* Assignment Operators
* Equality Operators
* Not Equal to operator

//Define a quantity variable, take cost variable to define the cost, Take user input for the Quantity he wants to purchase if the quantity is less than the quantity defined , then calculate total cost and reduce the quantity in stock

Window----Gobal object in javascript---Dom(Document Object Module)---Bom(Browser Object Module)
1.Create an Array of Cities sort them in the alphabetical order.

2.Create an Array of Products in Javascript
with Key value pairs ProductId, ProductName, ProductPrice,Category
Find all the Products whose price is above>2000, Print the result using foreach loop,
Find all the Products which belongs to particualr Category

3. * Create an h3 tag in Html with content and add content Hexaware to it.
   * Using Dom Manipulation change the content to Hexaware Javascript Training session


# Cloud Concepts
* Azure ----Microsoft
* AWS ------Amazon
* GCP-----Google

# Before VM and Cloud
* Cost involved in setting up datacenter was high
* Require highly qualified team 
* wastage of resources

# Virtualization
* It is the process which minimizes wastage of resources by running multiple applications on one server
* Hypervisor,----Logically seperates the servers,
* Increased efficiency

# Cloud
* Cloud Computing---it is the use of remote servers on the internet, to store data, host application, than your local server.
 * Risk analysis, Powersupply, fault tolerance taken care by cloud providers.

 # Cloud Service Model
  * Iaas
  * Paas
  * Saas

# Create an account with Azure---Portal.azure.com
 * Azure DataCenters----
 * Azure Geography---an area of the world that contains azure regions
  Us, India, UK, China
* Azure Regions---Set of datacenters connected through networks.
              -- Each region can have multiple datacenters.
* Azure Availability zone----physical location within the azure region
   * Availability zone1    availability zone 2    availability zone3
   * fault Domain---if the the powersupply in the speicfic rack goes faulty, only those servers in that rack goes fault

  * Availability Set-----logical grouping for isolated virtual Machines resources from each other

* Resource -----Resources are instances of azure Services(virtual machines, databases, storage accounts)
* Resource Group--- Devloping a dotnet application
    * Dev Environment +Ide----Visual Studio----Virtual Machine which has hosting development Env
    * Sql Server----Database Service
    * Datastorage---Images, Files

    Dev Team, TestingTeam, Production team


# IAM
Users----userEmail and pwd ceated by system department
Policies--->Granting permission to access Resources-- used for Authorization
Groups----->Create multiple groups
            * Development
            * DBAdmin
            *QA
            * Others
Roles----Db Service in cloud, dev service on premise---Roles
