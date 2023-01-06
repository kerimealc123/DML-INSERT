# DML-INSERT

//DML  insert (insertsObjects with list)
Account acc=new Account(name='deloitte', phone='2222');
insert acc;

List<Contact> conList = new List<Contact> {
    new Contact(FirstName='Joe',LastName='Smith',Department='Finance'),
        new Contact(FirstName='Kathy',LastName='Smith',Department='Technology'),
        new Contact(FirstName='Caroline',LastName='Roth',Department='Finance'),
        new Contact(FirstName='Kim',LastName='Shain',Department='Education')};
            
/*List<Account> accList = new List<Account>{
new Account(FirstName='mett',LastName='microsft', phone='222')
    new Account(FirstName='sam',LastName='bosch', phone='999')};
        insert accList};*/
                
List<Contact> updateCon=new List<Contact>()
for(Contact a:conList){
    if(a.firstname=='caroline'){
        a.lastname=='alici';
        updateCon.add(a);
    }           
            }
                        
update updateCon;
            
