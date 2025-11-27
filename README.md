# C_5
 Swaping4 number
#include <stdio.h>
#include <stdlib.h>
struct node {
    int vertex;
    struct node* next;
};
int main(){
    int v=5;
    struct node* adj[5];
    for(int i=0;i<;i++) adj[i]=NULL;
    
    struct node* temp= malloc(sizeof(struct nide));
    temp->vertex = v;
    temp->next = NULL;
    return temp;
};
adj[0]= create(1);
adj[0]->next = create(2);
adj[1]= create(0);
adj[1]->next = create(3);
adj[1]->next->next = create(4);
adj[2]= create(0);
adj[3]= create(1);
adj[4]= create(1);
printf("graph network...\n");
for(int i=0;i<v;i++){
    printf("%d->", i);
    struct node* temp= adj[1];
    while(temp){
        printf("%d ",temp->vertex);
        temp= temp->next;
        
    }
printf("\n");
}
return 0;
}

