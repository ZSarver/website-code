Questions Prompted by Student Mistakes, Pt. 1
#############################################

:date: 2015-10-15 13:22
:tags: math, questions
:category: blog
:slug: questions-from-mistakes-1
:authors: Zachary Sarver
:summary: Students do silly things. Let's think about silly things.

 .. role:: raw-latex(raw)
    :format: latex html

 .. These define a role (that double quote thing) for inline latex

I'm introducing a new series in this post, called "Questions Prompted by Student
Mistakes." I'm deliberately going to write these in more detail that is
necessary so that non-mathematicians can read them.

On a quiz I graded recently, I saw the following:

.. raw:: latex html
         
   \[ \cos\left(\frac{2}{x}\right) = \frac{\cos 2}{\cos x} = \frac{2}{x} \]

because :raw-latex:`\( \cos \)` totally works like that. So this prompted the
question, is there a function :raw-latex:`\( f: \mathbb{R} \to \mathbb{R} \)`
such that :raw-latex:`\( \frac{f(a)}{f(b)} = \frac{a}{b} \)` for all real
numbers :raw-latex:`\( a,b \)` with :raw-latex:`\( b \neq 0 \)`?

Clearly we can do this for nontrivial linear functions. Every nontrivial linear
function :raw-latex:`\( f: \mathbb{R} \to \mathbb{R} \)` is of the form
:raw-latex:`\( f(x) = \alpha x \)` where :raw-latex:`\( \alpha \)` is your
favorite non-zero constant. We have that

.. raw:: latex html
         
   \[ \frac{f(a)}{f(b)} = \frac{\alpha a}{\alpha b} = \frac{a}{b} \]

So the question is, then, are linear functions the only ones for which this
property holds? Click the button below to see the answer.

.. raw:: latex html
         
   <div id="spoiler" style="display:none">
         Yes. Suppose \( \frac{f(a)}{f(b)} = \frac{a}{b} \). Then \( f(a) =
         \frac{a}{b}\cdot f(b) \), so \( f(a) \) must be a scalar multiple of \(
         f(b) \) for each pair of \( a \) and \( b \). In particular, then, for
         \( b = 1 \) we have that \( f(a) = \frac{a}{1}\cdot f(1) = af(1)
         \). Thus the value of \( f(1) \) determines the entire function. Let \(
         f(1) = \alpha \), so then \( f(a) = \alpha a \), and \( f \) is linear.
   </div>
   <button title="Click to show/hide content" type="button"
   onclick="if(document.getElementById('spoiler') .style.display=='none')
   {document.getElementById('spoiler')
   .style.display=''}else{document.getElementById('spoiler')
   .style.display='none'}">Show/Hide Solution</button>
