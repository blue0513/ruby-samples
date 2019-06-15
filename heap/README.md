# myheap.rb
def initialize(n)  
いつもの(初期化用)  
値を引数に削除・追加の操作を行いたかったので、  
値とindexを結ぶためのHashを持ってます  

def push(current_value)  
要素の追加・重複要素は追加できません。  
(値をもとに削除操作を行う都合上そうしています)  

def delete(delete_target_value)  
値を引数に、要素の削除を行います  

def top  
最小要素へのアクセス  

def check_valid  
デバッグ用に作ってます。  
親子関係が正しくないノードがあるとraiseします  

def change(index_i, index_j)  
要素の入れ替えメソッドです。  