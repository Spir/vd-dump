# Vd dump

An improved var_dump for CodeIgniter, easier to read output with colors and more infos.

## Usage

simply load the library:

<code>
$this->load->library('Vd');
</code>

Then when you want to debug a var simple:

<code>
vd::dump($var);
</code>

This will directly output the debug.


If you want to output elsewhere you can set the return parameter to true:

<code>
$debug = vd::dump($var, 'My var name here', TRUE);
</code>