no-friendly-fire
================

#1.
just add to be boddom of your init.sqf this:

~~~~
  if (!isDedicated) then {
    // no friendly fire
    fnc_usec_damageHandler = compile preprocessFileLineNumbers "dayz_code\compile\fn_damageHandler.sqf";
  };
~~~~

enjoy and report all bugs u find :)
