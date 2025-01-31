*********************************
Support neural networks types
*********************************

	**Single layer perceptron**
		- create function: `neurolab.net.newp() <http://packages.python.org/neurolab/lib.html#neurolab.net.newp>`_
		- example of use: `newp <http://packages.python.org/neurolab/ex_newp.html>`_
		- default train function: `neurolab.train.train_delta() <http://packages.python.org/neurolab/lib.html#neurolab.train.train_delta>`_
		- support train functions: train_gd, train_gda, train_gdm, train_gdx, train_rprop, train_bfgs, train_cg
	
	**Multilayer feed forward perceptron**
		- create function: `neurolab.net.newff() <http://packages.python.org/neurolab/lib.html#neurolab.net.newff>`_
		- example of use: `newff <http://packages.python.org/neurolab/ex_newff.html>`_
		- default train function: `neurolab.train.train_bfgs() <http://packages.python.org/neurolab/lib.html#neurolab.train.train_bfgs>`_
		- support train functions: train_gd, train_gda, train_gdm, train_rprop, train_bfgs, train_cg
		
	**Competing layer (Kohonen Layer)**
		- create function: `neurolab.net.newc() <http://packages.python.org/neurolab/lib.html#neurolab.net.newc>`_
		- example of use: `newc <http://packages.python.org/neurolab/ex_newc.html>`_
		- default train function: `neurolab.train.train_cwta() <http://packages.python.org/neurolab/lib.html#neurolab.train.train_cwta>`_
		- support train functions: train_wta
		
	**Learning Vector Quantization (LVQ)**
		- create function: `neurolab.net.newlvq() <http://packages.python.org/neurolab/lib.html#neurolab.net.newlvq>`_
		- example of use: `newlvq <http://packages.python.org/neurolab/ex_newlvq.html>`_
		- default train function: `neurolab.train.train_lvq() <http://packages.python.org/neurolab/lib.html#neurolab.train.train_lvq>`_
	
	**Elman Recurrent network**
		- create function: `neurolab.net.newelm() <http://packages.python.org/neurolab/lib.html#neurolab.net.newelm>`_
		- example of use: `newelm <http://packages.python.org/neurolab/ex_newelm.html>`_
		- default train function: `neurolab.train.train_gdx() <http://packages.python.org/neurolab/lib.html#neurolab.train.train_gdx>`_
		- support train functions: train_gd, train_gda, train_gdm, train_rprop, train_bfgs, train_cg
	
	**Hopfield Recurrent network**
		- create function: `neurolab.net.newhop() <http://packages.python.org/neurolab/lib.html#neurolab.net.newhop>`_
		- example of use: `newhop <http://packages.python.org/neurolab/ex_newhop.html>`_
	**Hemming Recurrent network**
		- create function: `neurolab.net.newhem() <http://packages.python.org/neurolab/lib.html#neurolab.net.newhem>`_
		- example of use: `newhem <http://packages.python.org/neurolab/ex_newhem.html>`_
