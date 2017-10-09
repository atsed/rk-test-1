#include <iostream>
using namespace std;

struct Node {
    Node *next;
    int data;
};

template <class T>
class Linked_List {
private:
    Node *head;
    Node *tail;
public:
    Linked_List():head(0), tail(0){};
    void push_back(T val);
    void push_front(T val);
    void reverse();
    void display() const;
    ~Linked_List();
};
template <class T>
void Linked_List<T>::push_front(T val) {
    Node *newNode = new Node;

    newNode->data = val;
    newNode->next = head;

    head = newNode;

    if(tail==0)
        tail = head;
}
template <class T>
void Linked_List<T>::push_back(T val) {
    Node *newNode = new Node;

    newNode->data = val;
    newNode->next = 0;

    if(tail==0)
    {
        head = tail = newNode;
        return;
    }

    tail->next = newNode;
    tail = newNode;
}
template <class T>
Linked_List<T>::~Linked_List() {
    Node *tmp;
    while(head)
    {
        tmp = head;
        head = head->next;
        delete tmp;
    }
}
template <class T>
void Linked_List<T>::display() const {
    Node *curr = head;

    while(curr) {
        cout<<curr->data<<' ';
        curr = curr->next;
    }
}
template <class T>
void Linked_List<T>::reverse() {
    if (head == 0)
        return;

    tail = head;

    Node *curr = head->next;
    tail->next = 0;
    Node *right;

    while(curr) {
        right = curr->next;
        curr->next = head;
        head = curr;
        curr = right;
    }

    tail->next = 0;
}

int main() {
    Linked_List<int> intList;
    intList.push_front(3);
    intList.push_front(2);
    intList.push_front(1);
    intList.push_back(4);
    intList.push_back(5);
    intList.push_back(6);
    cout << "Normal: ";
    intList.display();
    intList.reverse();
    cout << "\nReversed: ";
    intList.display();
    cout << endl;

    return 0;
}
