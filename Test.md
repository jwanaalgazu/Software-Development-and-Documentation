# Test Document  <img width="10%" align="Right" src="https://github.com/jwanadude/Software-Development-and-Documentation/blob/main/09162016_043813Diamond123.jpg" />
_Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellus viverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiam ultricies nisi vel augue. Curabitur ullamcorper ultricies nisi. Nam eget dui. Etiam rhoncus. Maecenas tempus, tellus eget condimentum rhoncus, sem quam semper libero, sit amet adipiscing sem neque sed ipsum. Nam quam nunc, blandit vel, luctus pulvinar, hendrerit id, lorem. Maecenas nec odio et ante tincidunt tempus. Donec vitae sapien ut libero venenatis faucibus. Nullam quis ante. Etiam sit amet orci eget eros faucibus tincidunt. Duis leo. Sed fringilla mauris sit amet nibh. Donec sodales sagittis magna. Sed consequat, leo eget bibendum sodales, augue velit cursus nunc,_

## Subform1
 vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus.
 **_ vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus._**
 
 ### [ASU](https://www.asu.edu.jo/) :-
<img align="Right" src="https://github.com/jwanadude/Software-Development-and-Documentation/assets/140501135/a7fe076d-e286-4e16-8879-c79767cdd10e" /> 

 - Jwana Al-Gazu
 - SE
 - Software Development and documentation

### SDD:-
1. Data model
2. UI
3. Archetictural design

# Students Major:-

|  Students     |   Major       | 
| ------------- |:-------------:| 
|   Jwana       |    SE         |
|   Shahd       |    CS         |   
|   Dimah       |    SE         |    

# Java Code:-
```
package queue;
import java.util.Scanner;
/**
 *
 * @author user
 */
public class App1 {
    
    public static <T> void printQueue(ArrayBoundedQueue<T> f){
        ArrayBoundedQueue<T> temp = new ArrayBoundedQueue<>();
        while (!f.isEmpty()){
            T e = f.dequeue();
            System.out.println(e);
            temp.enqueue(e);
        }
        while(!temp.isEmpty())
            f.enqueue(temp.dequeue());        
    }
     
    public static void main(String[] args)
    {
        Scanner conIn = new Scanner(System.in);
        String line;
        
        ArrayBoundedQueue<String> r = new ArrayBoundedQueue<>();
        
        for (int i=1; i<=3;i++)
        {
            System.out.print("Enter a line text : ");
            line= conIn.nextLine();
            r.enqueue(line);           
        }
        printQueue(r);
        
    }
    
}
```

# Tasks List:-
- [x] Study.
- [ ] Play.
- [x] Workshps. 














