# apex-eval

APEX implementation of Eval() method for evaluation of mathematic expressions and text expressions.

System.assertEquals(15.0,   EXP_Eval.mathEval(new List<Object> {10,5,'+'}));
System.assertEquals(5.0,   EXP_Eval.mathEval(new List<Object> {10,5,'-'}));
System.assertEquals(0.0,   EXP_Eval.mathEval(new List<Object> {3,1,'<='}));
System.assertEquals(1.0,   EXP_Eval.mathEval(new List<Object> {3,3,'=='}));
System.assertEquals(1.0,   EXP_Eval.textEval(new List<Object> {'Tree','Tree','=='}));
System.assertEquals(0.0,   EXP_Eval.textEval(new List<Object> {'Tee','Foset','=='}));

Source Blog: https://iandrosov.github.io/APEX-Expression-Eval/
