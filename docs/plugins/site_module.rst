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

.. _ansible_collections.networktocode.nautobot.site_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

networktocode.nautobot.site -- Creates or removes sites from Nautobot
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This plugin is part of the `networktocode.nautobot collection <https://galaxy.ansible.com/networktocode/nautobot>`_ (version 3.3.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install networktocode.nautobot`.

    To use it in a playbook, specify: :code:`networktocode.nautobot.site`.

.. version_added

.. versionadded:: 1.0.0 of networktocode.nautobot

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- Creates or removes sites from Nautobot


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
                    <div class="ansibleOptionAnchor" id="parameter-asn"></div>
                    <b>asn</b>
                    <a class="ansibleOptionLink" href="#parameter-asn" title="Permalink to this option"></a>
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
                                            <div>The ASN associated with the site</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-comments"></div>
                    <b>comments</b>
                    <a class="ansibleOptionLink" href="#parameter-comments" title="Permalink to this option"></a>
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
                                            <div>Comments for the site. This can be markdown syntax</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-contact_email"></div>
                    <b>contact_email</b>
                    <a class="ansibleOptionLink" href="#parameter-contact_email" title="Permalink to this option"></a>
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
                                            <div>Contact email for site</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-contact_name"></div>
                    <b>contact_name</b>
                    <a class="ansibleOptionLink" href="#parameter-contact_name" title="Permalink to this option"></a>
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
                                            <div>Name of contact for site</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-contact_phone"></div>
                    <b>contact_phone</b>
                    <a class="ansibleOptionLink" href="#parameter-contact_phone" title="Permalink to this option"></a>
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
                                            <div>Contact phone number for site</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-custom_fields"></div>
                    <b>custom_fields</b>
                    <a class="ansibleOptionLink" href="#parameter-custom_fields" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">dictionary</span>
                                                                    </div>
                                          <div style="font-style: italic; font-size: small; color: darkgreen">
                        added in 3.0.0 of networktocode.nautobot
                      </div>
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>must exist in Nautobot</div>
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
                                            <div>The description of the prefix</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-facility"></div>
                    <b>facility</b>
                    <a class="ansibleOptionLink" href="#parameter-facility" title="Permalink to this option"></a>
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
                                            <div>Data center provider or facility, ex. Equinix NY7</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-latitude"></div>
                    <b>latitude</b>
                    <a class="ansibleOptionLink" href="#parameter-latitude" title="Permalink to this option"></a>
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
                                            <div>Latitude in decimal format</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-longitude"></div>
                    <b>longitude</b>
                    <a class="ansibleOptionLink" href="#parameter-longitude" title="Permalink to this option"></a>
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
                                            <div>Longitude in decimal format</div>
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
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>Name of the site to be created</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-physical_address"></div>
                    <b>physical_address</b>
                    <a class="ansibleOptionLink" href="#parameter-physical_address" title="Permalink to this option"></a>
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
                                            <div>Physical address of site</div>
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
                    <div class="ansibleOptionAnchor" id="parameter-region"></div>
                    <b>region</b>
                    <a class="ansibleOptionLink" href="#parameter-region" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">raw</span>
                                                                    </div>
                                          <div style="font-style: italic; font-size: small; color: darkgreen">
                        added in 3.0.0 of networktocode.nautobot
                      </div>
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>The region that the site should be associated with</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-shipping_address"></div>
                    <b>shipping_address</b>
                    <a class="ansibleOptionLink" href="#parameter-shipping_address" title="Permalink to this option"></a>
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
                                            <div>Shipping address of site</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-slug"></div>
                    <b>slug</b>
                    <a class="ansibleOptionLink" href="#parameter-slug" title="Permalink to this option"></a>
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
                                            <div>URL-friendly unique shorthand</div>
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
                    <div class="ansibleOptionAnchor" id="parameter-status"></div>
                    <b>status</b>
                    <a class="ansibleOptionLink" href="#parameter-status" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">raw</span>
                                                                    </div>
                                          <div style="font-style: italic; font-size: small; color: darkgreen">
                        added in 3.0.0 of networktocode.nautobot
                      </div>
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>Status of the site</div>
                                            <div>Required if <em>state=present</em> and does not exist yet</div>
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
                                            <div>Any tags that the prefix may need to be associated with</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-tenant"></div>
                    <b>tenant</b>
                    <a class="ansibleOptionLink" href="#parameter-tenant" title="Permalink to this option"></a>
                    <div style="font-size: small">
                        <span style="color: purple">raw</span>
                                                                    </div>
                                          <div style="font-style: italic; font-size: small; color: darkgreen">
                        added in 3.0.0 of networktocode.nautobot
                      </div>
                                                        </td>
                                <td>
                                                                                                                                                            </td>
                                                                <td>
                                            <div>The tenant the site will be assigned to</div>
                                                        </td>
            </tr>
                                <tr>
                                                                <td colspan="1">
                    <div class="ansibleOptionAnchor" id="parameter-time_zone"></div>
                    <b>time_zone</b>
                    <a class="ansibleOptionLink" href="#parameter-time_zone" title="Permalink to this option"></a>
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
                                            <div>Timezone associated with the site, ex. America/Denver</div>
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
                                            <div>If <code>no</code>, SSL certificates will not be validated.
    This should only be used on personally controlled sites using self-signed certificates.</div>
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

    
    - name: "Test Nautobot site module"
      connection: local
      hosts: localhost
      gather_facts: False
      tasks:
        - name: Create site within Nautobot with only required information
          networktocode.nautobot.site:
            url: http://nautobot.local
            token: thisIsMyToken
            name: Test - Colorado
            status: active
            state: present

        - name: Delete site within nautobot
          networktocode.nautobot.site:
            url: http://nautobot.local
            token: thisIsMyToken
            name: Test - Colorado
            state: absent

        - name: Create site with all parameters
          networktocode.nautobot.site:
            url: http://nautobot.local
            token: thisIsMyToken
            name: Test - California
            status: Planned
            region: Test Region
            tenant: Test Tenant
            facility: EquinoxCA7
            asn: 65001
            time_zone: America/Los Angeles
            description: This is a test description
            physical_address: Hollywood, CA, 90210
            shipping_address: Hollywood, CA, 90210
            latitude: 10.100000
            longitude: 12.200000
            contact_name: Jenny
            contact_phone: 867-5309
            contact_email: jenny@changednumber.com
            slug: test-california
            comments: ### Placeholder
            state: present




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
                    <div class="ansibleOptionAnchor" id="return-site"></div>
                    <b>site</b>
                    <a class="ansibleOptionLink" href="#return-site" title="Permalink to this return value"></a>
                    <div style="font-size: small">
                      <span style="color: purple">dictionary</span>
                                          </div>
                                    </td>
                <td>on creation</td>
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

- Mikhail Yohman (@FragmentedPacket)



.. Parsing errors

