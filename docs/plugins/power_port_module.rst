.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. role:: ansible-attribute-support-label
.. role:: ansible-attribute-support-property
.. role:: ansible-attribute-support-full
.. role:: ansible-attribute-support-partial
.. role:: ansible-attribute-support-none
.. role:: ansible-attribute-support-na

.. Anchors

.. _ansible_collections.networktocode.nautobot.power_port_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

networktocode.nautobot.power_port -- Create, update or delete power ports within Nautobot
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This plugin is part of the `networktocode.nautobot collection <https://galaxy.ansible.com/networktocode/nautobot>`_ (version 3.3.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install networktocode.nautobot`.

    To use it in a playbook, specify: :code:`networktocode.nautobot.power_port`.

.. version_added

.. versionadded:: 1.0.0 of networktocode.nautobot

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- Creates, updates or removes power ports from Nautobot


.. Aliases


.. Requirements

Requirements
------------
The below requirements are needed on the host that executes this module.

- pynautobot


.. Options

Parameters
----------

.. raw:: html

    <table  border=0 cellpadding=0 class="documentation-table">
        <tr>
            <th colspan="1">Parameter</th>
            <th>Choices/<font color="blue">Defaults</font></th>
                        <th width="100%">Comments</th>
        </tr>
                    <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-allocated_draw"></div>
                    <b>allocated_draw</b>
                    <a class="ansibleOptionLink" href="#parameter-allocated_draw" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">integer</span>
                                                                    </div>
                                          <div style="font-style: italic; font-size: small; color: darkgreen">
                        added in 3.0.0 of networktocode.nautobot
                      </div>
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>The allocated draw of the power port in watt</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-description"></div>
                    <b>description</b>
                    <a class="ansibleOptionLink" href="#parameter-description" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">string</span>
                                                                    </div>
                                          <div style="font-style: italic; font-size: small; color: darkgreen">
                        added in 3.0.0 of networktocode.nautobot
                      </div>
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>Description of the power port</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-device"></div>
                    <b>device</b>
                    <a class="ansibleOptionLink" href="#parameter-device" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">raw</span>
                                                 / <span style="color: red">required</span>                    </div>
                                          <div style="font-style: italic; font-size: small; color: darkgreen">
                        added in 3.0.0 of networktocode.nautobot
                      </div>
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>The device the power port is attached to</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-maximum_draw"></div>
                    <b>maximum_draw</b>
                    <a class="ansibleOptionLink" href="#parameter-maximum_draw" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">integer</span>
                                                                    </div>
                                          <div style="font-style: italic; font-size: small; color: darkgreen">
                        added in 3.0.0 of networktocode.nautobot
                      </div>
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>The maximum permissible draw of the power port in watt</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-name"></div>
                    <b>name</b>
                    <a class="ansibleOptionLink" href="#parameter-name" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">string</span>
                                                 / <span style="color: red">required</span>                    </div>
                                          <div style="font-style: italic; font-size: small; color: darkgreen">
                        added in 3.0.0 of networktocode.nautobot
                      </div>
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>The name of the power port</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-query_params"></div>
                    <b>query_params</b>
                    <a class="ansibleOptionLink" href="#parameter-query_params" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">list</span>
                         / <span style="color: purple">elements=string</span>                                            </div>
                                          <div style="font-style: italic; font-size: small; color: darkgreen">
                        added in 3.0.0 of networktocode.nautobot
                      </div>
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>This can be used to override the specified values in ALLOWED_QUERY_PARAMS that is defined</div>
                                            <div>in plugins/module_utils/utils.py and provides control to users on what may make</div>
                                            <div>an object unique in their environment.</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-state"></div>
                    <b>state</b>
                    <a class="ansibleOptionLink" href="#parameter-state" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">string</span>
                                                                    </div>
                                                        </td>
                                <td>
                                                                                                                            <ul style="margin: 0; padding: 0"><b>Choices:</b>
                                                                                                                                                                <li>absent</li>
                                                                                                                                                                                                <li><div style="color: blue"><b>present</b>&nbsp;&larr;</div></li>
                                                                                    </ul>
                                                                            </td>
                                                                <td>
                                            <div>Use <code>present</code> or <code>absent</code> for adding or removing.</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-tags"></div>
                    <b>tags</b>
                    <a class="ansibleOptionLink" href="#parameter-tags" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">list</span>
                         / <span style="color: purple">elements=raw</span>                                            </div>
                                          <div style="font-style: italic; font-size: small; color: darkgreen">
                        added in 3.0.0 of networktocode.nautobot
                      </div>
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>Any tags that the power port may need to be associated with</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-token"></div>
                    <b>token</b>
                    <a class="ansibleOptionLink" href="#parameter-token" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">string</span>
                                                 / <span style="color: red">required</span>                    </div>
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>The token created within Nautobot to authorize API access</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-type"></div>
                    <b>type</b>
                    <a class="ansibleOptionLink" href="#parameter-type" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">string</span>
                                                                    </div>
                                          <div style="font-style: italic; font-size: small; color: darkgreen">
                        added in 3.0.0 of networktocode.nautobot
                      </div>
                                                        </td>
                                <td>
                                                                                                                            <ul style="margin: 0; padding: 0"><b>Choices:</b>
                                                                                                                                                                <li>iec-60320-c6</li>
                                                                                                                                                                                                <li>iec-60320-c8</li>
                                                                                                                                                                                                <li>iec-60320-c14</li>
                                                                                                                                                                                                <li>iec-60320-c16</li>
                                                                                                                                                                                                <li>iec-60320-c20</li>
                                                                                                                                                                                                <li>iec-60309-p-n-e-4h</li>
                                                                                                                                                                                                <li>iec-60309-p-n-e-6h</li>
                                                                                                                                                                                                <li>iec-60309-p-n-e-9h</li>
                                                                                                                                                                                                <li>iec-60309-2p-e-4h</li>
                                                                                                                                                                                                <li>iec-60309-2p-e-6h</li>
                                                                                                                                                                                                <li>iec-60309-2p-e-9h</li>
                                                                                                                                                                                                <li>iec-60309-3p-e-4h</li>
                                                                                                                                                                                                <li>iec-60309-3p-e-6h</li>
                                                                                                                                                                                                <li>iec-60309-3p-e-9h</li>
                                                                                                                                                                                                <li>iec-60309-3p-n-e-4h</li>
                                                                                                                                                                                                <li>iec-60309-3p-n-e-6h</li>
                                                                                                                                                                                                <li>iec-60309-3p-n-e-9h</li>
                                                                                                                                                                                                <li>nema-5-15p</li>
                                                                                                                                                                                                <li>nema-5-20p</li>
                                                                                                                                                                                                <li>nema-5-30p</li>
                                                                                                                                                                                                <li>nema-5-50p</li>
                                                                                                                                                                                                <li>nema-6-15p</li>
                                                                                                                                                                                                <li>nema-6-20p</li>
                                                                                                                                                                                                <li>nema-6-30p</li>
                                                                                                                                                                                                <li>nema-6-50p</li>
                                                                                                                                                                                                <li>nema-l5-15p</li>
                                                                                                                                                                                                <li>nema-l5-20p</li>
                                                                                                                                                                                                <li>nema-l5-30p</li>
                                                                                                                                                                                                <li>nema-l5-50p</li>
                                                                                                                                                                                                <li>nema-l6-20p</li>
                                                                                                                                                                                                <li>nema-l6-30p</li>
                                                                                                                                                                                                <li>nema-l6-50p</li>
                                                                                                                                                                                                <li>nema-l14-20p</li>
                                                                                                                                                                                                <li>nema-l14-30p</li>
                                                                                                                                                                                                <li>nema-l21-20p</li>
                                                                                                                                                                                                <li>nema-l21-30p</li>
                                                                                                                                                                                                <li>cs6361c</li>
                                                                                                                                                                                                <li>cs6365c</li>
                                                                                                                                                                                                <li>cs8165c</li>
                                                                                                                                                                                                <li>cs8265c</li>
                                                                                                                                                                                                <li>cs8365c</li>
                                                                                                                                                                                                <li>cs8465c</li>
                                                                                                                                                                                                <li>ita-e</li>
                                                                                                                                                                                                <li>ita-f</li>
                                                                                                                                                                                                <li>ita-ef</li>
                                                                                                                                                                                                <li>ita-g</li>
                                                                                                                                                                                                <li>ita-h</li>
                                                                                                                                                                                                <li>ita-i</li>
                                                                                                                                                                                                <li>ita-j</li>
                                                                                                                                                                                                <li>ita-k</li>
                                                                                                                                                                                                <li>ita-l</li>
                                                                                                                                                                                                <li>ita-m</li>
                                                                                                                                                                                                <li>ita-n</li>
                                                                                                                                                                                                <li>ita-o</li>
                                                                                    </ul>
                                                                            </td>
                                                                <td>
                                            <div>The type of the power port</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-url"></div>
                    <b>url</b>
                    <a class="ansibleOptionLink" href="#parameter-url" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">string</span>
                                                 / <span style="color: red">required</span>                    </div>
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>URL of the Nautobot instance resolvable by Ansible control host</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-validate_certs"></div>
                    <b>validate_certs</b>
                    <a class="ansibleOptionLink" href="#parameter-validate_certs" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">raw</span>
                                                                    </div>
                                                        </td>
                                <td>
                                                                                                                                                                                                                <b>Default:</b><br/><div style="color: blue">"yes"</div>
                                    </td>
                                                                <td>
                                            <div>If <code>no</code>, SSL certificates will not be validated. This should only be used on personally controlled sites using self-signed certificates.</div>
                                                        </td>
            </tr>
                        </table>
    <br/>

.. Attributes


.. Notes

Notes
-----

.. note::
   - Tags should be defined as a YAML list
   - This should be ran with connection ``local`` and hosts ``localhost``

.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: "Test Nautobot modules"
      connection: local
      hosts: localhost
      gather_facts: False

      tasks:
        - name: Create power port within Nautobot with only required information
          networktocode.nautobot.power_port:
            url: http://nautobot.local
            token: thisIsMyToken
            name: Test Power Port
            device: Test Device
            state: present

        - name: Update power port with other fields
          networktocode.nautobot.power_port:
            url: http://nautobot.local
            token: thisIsMyToken
            name: Test Power Port
            device: Test Device
            type: iec-60320-c6
            allocated_draw: 16
            maximum_draw: 80
            description: power port description
            state: present

        - name: Delete power port within nautobot
          networktocode.nautobot.power_port:
            url: http://nautobot.local
            token: thisIsMyToken
            name: Test Power Port
            device: Test Device
            state: absent




.. Facts


.. Return values

Return Values
-------------
Common return values are documented :ref:`here <common_return_values>`, the following are the fields unique to this module:

.. raw:: html

    <table border=0 cellpadding=0 class="documentation-table">
        <tr>
            <th colspan="1">Key</th>
            <th>Returned</th>
            <th width="100%">Description</th>
        </tr>
                    <tr>
                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="return-msg"></div>
                    <b>msg</b>
                    <a class="ansibleOptionLink" href="#return-msg" title="Permalink to this return value"></a>
                    <div style="font-size: small">
                      <span style="color: purple">string</span>
                                          </div>
                                    </td>
                <td>always</td>
                <td>
                                            <div>Message indicating failure or info about what has been achieved</div>
                                        <br/>
                                                        </td>
            </tr>
                                <tr>
                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="return-power_port"></div>
                    <b>power_port</b>
                    <a class="ansibleOptionLink" href="#return-power_port" title="Permalink to this return value"></a>
                    <div style="font-size: small">
                      <span style="color: purple">dictionary</span>
                                          </div>
                                    </td>
                <td>success (when <em>state=present</em>)</td>
                <td>
                                            <div>Serialized object as created or already existent within Nautobot</div>
                                        <br/>
                                                        </td>
            </tr>
                        </table>
    <br/><br/>

..  Status (Presently only deprecated)


.. Authors

Authors
~~~~~~~

- Tobias Groß (@toerb)



.. Parsing errors

