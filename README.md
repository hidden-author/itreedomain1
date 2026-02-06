# Rocq code for "A Domain-Theoretic Framework for Composing Effectful Programs and Their Equations"

_make_ to compile (please use [Rocq 9.0.0](https://rocq-prover.org/))

Contents:
<dl>
<dt> domain/ </dt>
<dd> domain theory (cf. Section 2 and part of the Appendix in the paper) </dd>

<dt> examples/ </dt> 
<dd> Syracuse and FlipWhileTrue exampels from Section 6 <p>
          N.B.  Syracuse.v takes a bit longer to compile due to setoid rewrites </p> </dd>
		  
          
<dt> itree/  </dt>   
<dd> interaction trees : definition, monadic structure, fold, equivalence, coproduct  <p>
					(cf. Sections 4 and 5) </p> </dd>
<dt> monad/ </dt>			
<dd> CPO-monads (cf. Section 3) </dd>

<dt> prob/ </dt>			
<dd> probability CPO-monad (various aspects covered in Examples 6, 16, 19, 23)
</dd>

<dt> state/ </dt>			
<dd> state transformer CPO-monad (various aspects covered in Examples 7, 17, 20, 22)
</dd>

<dl> 
<dt> anonymous.pdf </dt>
<dd>  anonymyzed version of an earlier paper (for details about containers)</dd>


</dl> 

