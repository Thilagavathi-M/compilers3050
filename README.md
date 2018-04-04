# compilers3050

.folder Basic block and Flow graph-> generates dag from given set of c statements for a basic block. it generates leaders and blocks and dag for each blocks.

.folder Backpatching -> for a given boolean expression, create the true list, false list etc

.folder copy-constant -> it generates dag for a given block of statements and removes copy propagation, constant folding and common sub expression and generates optimized three address statements for that block.

.folder ifelse -> if a given "if" statement doesnt have a corresponding "else", add an empty "else{}" statement.

.folder loops -> convert the given "for" and "dowhile" loop to "while" loop such that its semantic meaning is maintained.

.folder symbol_table -> given a set of declaration statements, it generates its symbol table

.folder syntax_tree -> creates a syntax tree for an arithmetic expression
