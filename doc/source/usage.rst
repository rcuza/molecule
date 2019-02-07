Usage
=====

Check
^^^^^

Check will preform converge the instances, then run a check (converge again).

.. autoclass:: molecule.command.check.Check()
   :undoc-members:

Converge
^^^^^^^^

Converge will execute the sequence necessary to converge the instances.

.. autoclass:: molecule.command.converge.Converge()
   :undoc-members:

Create
^^^^^^

Create will start the instance(s) of the configured driver(s).

.. autoclass:: molecule.command.create.Create()
   :undoc-members:

Dependency
^^^^^^^^^^

Manage the role's dependencies.

.. autoclass:: molecule.command.dependency.Dependency()
   :undoc-members:

Destroy
^^^^^^^

Use the provisioner to destroy the instances.

.. autoclass:: molecule.command.destroy.Destroy()
   :undoc-members:



Idempotence
^^^^^^^^^^^

Use the provisioner to configure the instances and parse the output to
  determine idempotence.

.. autoclass:: molecule.command.idempotence.Idempotence()
   :undoc-members:

Init
^^^^

.. autoclass:: molecule.command.init.role.Role()
   :undoc-members:

.. autoclass:: molecule.command.init.scenario.Scenario()
   :undoc-members:

.. autoclass:: molecule.command.init.template.Template()
   :undoc-members:

Lint
^^^^

.. autoclass:: molecule.command.lint.Lint()
   :undoc-members:

List
^^^^

.. autoclass:: molecule.command.list.List()
   :undoc-members:

Login
^^^^^

.. autoclass:: molecule.command.login.Login()
   :undoc-members:

Matrix
^^^^^^

Matrix will display the subcommand's ordered list of actions, which can be
changed in `scenario`_ configuration.

.. _`scenario`: https://molecule.readthedocs.io/en/latest/configuration.html#scenario

.. autoclass:: molecule.command.matrix.Matrix()
   :undoc-members:

Prepare
^^^^^^^

.. autoclass:: molecule.command.prepare.Prepare()
   :undoc-members:

Side Effect
^^^^^^^^^^^

.. autoclass:: molecule.command.side_effect.SideEffect()
   :undoc-members:

Syntax
^^^^^^

.. autoclass:: molecule.command.syntax.Syntax()
   :undoc-members:

Test
^^^^

Test will execute the sequence necessary to test the instances.

.. autoclass:: molecule.command.test.Test()
   :undoc-members:

Verify
^^^^^^

.. autoclass:: molecule.command.verify.Verify()
   :undoc-members:
