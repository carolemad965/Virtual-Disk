# Virtual-Disk
We programmed a virtual storage space and programmed a lot of CMD commands using C#.
# Class 1 : virtual_disk  
1- intit() : void     
2- write_block(byte[],int) : void
3- get_block( int) : byte[] 
# Class 2 : fat 
1-fat()
2-intit() : void      
3-Write_Fat_Table() : void   
4-get_Fat_Table() : int[]      
5-print_Fat_Table() : void  
6-get_available_block() : int    
7-get_Next_block(int) :  int
8-set_Next_block(int ,int) :  void      
9-get_availble_Blocks() : int  
10-getfreespace() : int      
# Class 3 :  Directory 
1-Directory(char[], byte, int, Directory) 
2-GetDirectory_Entry() : 
3-Directory_Entry          
4-Write_Directory() : void 
5-Read_Directory() : void
6-search_directory(char[]) : int 
7-update_content(Directory_Entry) : void           
8- delete_directory() : void 
# Class 4: Directory_Entry
1-Directory_Entry( char[], byte, int)        
2-getBytes() : byte[]     
3-getDirectory_entry(byte[]) : void 
4- getDirectory_entry() :Directory_Entry 
# Class 5: cmd         
1- cmd()
2-check(string):bool           
3-md(char[]:void            
4- rd(char[]) :void         
5- cd(char[]) : void        
6- dir() : void
7-import(string) : void          
8- turnOn() : void 
# Class 6: file_entry 
1-file_entry(char[], byte, int, Directory, string,int)         
2-GetDirectory_Entry():Directory_Entry         
3-g_file_bytee(string):byte[]         
4-Write_file(): void         
5-Read_file() : void         
6-delete_file(file_entry) : void
