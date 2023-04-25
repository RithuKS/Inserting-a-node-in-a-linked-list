#include <stdio.h>
#include <stdlib.h>
struct node{
	int data;
	struct node *next;
};

struct node *start = NULL;

int main()
{
	struct node newnode= (struct node)malloc(sizeof(struct node));
	start = newnode;
	newnode -> data;
	newnode -> next= NULL;
	
	add_end(30);
	add_end(40);
	display();
	
}

void display()
{
	struct node *temp=start;
	while(temp!=NULL)
	{
		printf("data=%d selfadd=%d nextadd=%d", temp->data,temp,temp->next);
		temp=temp->next;
	}
}

void add_end(int info)
{
	struct node newnode = (struct node)malloc(sizeof(struct node));
	struct node *temp=start;
	while(temp->next !=NULL)
	{
		temp=temp-> next;
		temp->data=info;
		newnode->next=NULL;
	}
}
