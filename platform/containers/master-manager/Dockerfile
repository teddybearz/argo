# -*- coding: utf-8 -*-
#
# Copyright 2015-2016 Applatix, Inc. All rights reserved.
#
# Dockerfile for master-manager

FROM %%BUILDER_IMAGE_ID%%

COPY docker_build/root /
ENV PYTHONPATH /ax/python
ENV PATH /ax/bin:${PATH}

CMD ["master_manager"]
