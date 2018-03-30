# Remove-Duplicate
def remove_dup(my_list):
    my_list = (set('p','a','a','g''g','g','a','r','a','n','n'))
    s = set()
    remove_dup = list(set(my_list) - set(s))
    print(remove_dup)
    return remove_dup

def main():
    while True:
        try:
            l1 = input("enter list: ")
            if (len(l1) < 1):
                print ('my_list()')
            else:
                remove_dup(l1)

        
