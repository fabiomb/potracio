# potracio
A PHP port for of Potrace (http://potrace.sourceforge.net)


/*  Potracio - Port by Otamay (2017) (https://github.com/Otamay/potracio.git)
 * A PHP Port of Potrace (http://potrace.sourceforge.net),
 * ported from https://github.com/kilobtye/potrace. Info below:
 *
 *  Copyright (C) 2001-2013 Peter Selinger.
 *
 * A javascript port of Potrace (http://potrace.sourceforge.net).
 * 
 * Licensed under the GPL
 * 
 * Usage
 *   loadImageFromFile(file) : load image from File
 * 
 *   setParameter({para1: value, ...}) : set parameters
 *     parameters:
 *        turnpolicy ("black" / "white" / "left" / "right" / "minority" / "majority")
 *          how to resolve ambiguities in path decomposition. (default: "minority")       
 *        turdsize
 *          suppress speckles of up to this size (default: 2)
 *        optcurve (true / false)
 *          turn on/off curve optimization (default: true)
 *        alphamax
 *          corner threshold parameter (default: 1)
 *        opttolerance 
 *          curve optimization tolerance (default: 0.2)
 *       
 *   getSVG(size, opt_type) : return a string of generated SVG image.
 *                                    result_image_size = original_image_size * size
 *                                    optional parameter opt_type can be "curve"
 */
