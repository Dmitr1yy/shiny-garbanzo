//const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});

const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});

const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});

const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});

const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});

const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});

const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
const { assert } = require('chai');
const { testOptional, ListNode } = require('../extensions/index.js');
const { removeKFromList } = require('../src/remove-from-list.js');

it.optional = testOptional;

Object.freeze(assert);

function convertArrayToList(arr) {
  return arr.reverse().reduce((acc, cur) => {
    if (acc) {
      const node = new ListNode(cur);
      node.next = acc;
      return node;
    }

    return new ListNode(cur);
  }, null);
}

describe('Remove from list', () => {
  it.optional('should return the list without values equal to k', () => {
    const initial = convertArrayToList([3, 1, 2, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with double k)', () => {
    const initial = convertArrayToList([1, 2, 3, 3, 4, 5]);
    const expected = convertArrayToList([1, 2, 4, 5]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });

  it.optional('should return the list without values equal to k (with k at the end)', () => {
    const initial = convertArrayToList([1, 2, 3]);
    const expected = convertArrayToList([1, 2]);
    assert.deepEqual(removeKFromList(initial, 3), expected);
  });
});
# AssertionError [![Build Status](https://travis-ci.org/chaijs/assertion-error.png?branch=master)](https://travis-ci.org/chaijs/assertion-error)

> Error constructor for test and validation frameworks that implements standardized AssertionError specification.

## Installation

### Node.js
# AssertionError [![Build Status](https://travis-ci.org/chaijs/assertion-error.png?branch=master)](https://travis-ci.org/chaijs/assertion-error)

> Error constructor for test and validation frameworks that implements standardized AssertionError specification.

## Installation

### Node.js

`assertion-error` is available on [npm](http://npmjs.org).

    $ npm install assertion-error

### Component

`assertion-error` is available as a [component](https://github.com/component/component).

    $ component install chaijs/assertion-error

## License

(The MIT License)

Copyright (c) 2013 Jake Luer <jake@qualiancy.com> (http://qualiancy.com)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

`assertion-error` is available on [npm](http://npmjs.org).

    $ npm install assertion-error

### Component

`assertion-error` is available as a [component](https://github.com/component/component).

    $ component install chaijs/assertion-error

## License

(The MIT License)

Copyright (c) 2013 Jake Luer <jake@qualiancy.com> (http://qualiancy.com)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

