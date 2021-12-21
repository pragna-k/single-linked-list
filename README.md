# single-linked-list
struct size
{
    int data;
    struct slist *next;
}
type of struct slist node;
node*create(node*first)
{
    node*new,*prev;
    int x;
    printf("enter the data value"("enter -1 to stop"));
    scanf("%d",&x);
    while(x!=-1)
    {
        new=(node*malloc(scanf(node)));
        new->data=x;
        new->next=null;
        if(first==null)
        {
            first=new;
            prev=new;
        }
        else
        {
            prev->next=new;
            prev=new;
        }
        printf("enter data"("enter -1 to stop"));
        scanf("%d",&x);
        {
            return first;
        }
    }
}

